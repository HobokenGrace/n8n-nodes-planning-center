# PCO People Full Endpoint Support Plan

## Objective

Support every documented Planning Center People v2 endpoint in the n8n node.

This plan has two delivery bars:

1. Endpoint reachability: every People endpoint is callable from n8n.
2. First-class UX: every People endpoint is available as a typed n8n entity/operation.

## Current State

- The node currently supports two Planning Center products: People and Publishing.
- People currently exposes only six UI operations:
  - `createPerson`
  - `deletePerson`
  - `getPerson`
  - `getManyPeople`
  - `getFieldDefinition`
  - `updatePerson`
- `PeopleClient` already contains extra People helpers that are not exposed in the node UI.
- People execution is currently hand-wired through a large `if/else` block in `nodes/PlanningCenter/PlanningCenter.node.ts`.
- The current pattern already has drift:
  - UI operation: `getFieldDefinition`
  - execute branch: `listFieldDefinitions`
- There is no automated test suite.
- The bundled API docs cover 36 People resources and 502 operations, so the current hand-authored approach will not scale.

## OpenAPI Direction

- Use the OpenAPI spec as the source of truth for:
  - operation inventory
  - HTTP method and path
  - path, query, and body parameters
  - request and response schemas
  - coverage validation
- Do not blindly generate the entire n8n node UX from OpenAPI.
- Use a hybrid model:
  - generate the machine-truth layer
  - handcraft the n8n UX layer on top of it
- This is the right fit for the goal of supporting every endpoint without creating 500+ manually maintained property files and dispatch branches.

## Strategy

- Keep one Planning Center node.
- Change the People UX from `resource=people + operation` to `product=people + entity + operation`.
- Add a `People API Request` operation first so every endpoint becomes callable immediately.
- Generate a normalized People operation registry from the OpenAPI spec.
- Generate scaffolding and machine metadata from the OpenAPI spec, then feed that registry into shared n8n factories.
- Build typed UI and execution from the registry, with manual overrides where the UX needs to be more human-friendly.
- Use shared factories for repeated operation shapes:
  - collection get
  - single get
  - create
  - update
  - delete
  - action POST
  - linked/relationship endpoint
- Add shared query builders for:
  - `include`
  - `fields[...]`
  - `where[...]`
  - `filter[...]`
  - `order`
  - pagination
  - raw query override
- Add shared JSON:API response handling with a toggle:
  - default: normalized `data`
  - optional: full envelope with `data`, `included`, `meta`, `links`

## Generation Model

- Generate from OpenAPI:
  - operation manifest
  - path templates
  - supported params
  - request body schema references
  - response schema references
  - operation-to-entity mapping metadata
- Hand-author on top of generated metadata:
  - friendly entity and operation labels
  - load options
  - shared query UX
  - pagination UX
  - JSON:API body helpers
  - response normalization behavior
  - manual overrides for awkward or inconsistent endpoints
- Keep a small manual override layer for:
  - labels and descriptions
  - special action endpoints
  - loadOptions sources
  - any OpenAPI quirks or gaps
- Do not generate:
  - a giant `if/else` executor
  - one standalone property file per endpoint
  - duplicated request mapping code

## Node UX Target

- `Product`: People / Publishing
- `Entity`: Person, List, Workflow, Form, Household, etc.
- `Operation`: generated per entity
- Common options for applicable operations:
  - path IDs
  - `Return All`
  - `Limit`
  - `Include`
  - `Fields`
  - `Where`
  - `Filter`
  - `Order`
  - `Additional Query Parameters`
  - `Return Full Response`
- High-use load options:
  - campuses
  - field definitions
  - lists
  - workflows
  - forms
  - note categories

## Implementation Rules

- Do not add 500+ endpoints through hand-written `if/else` routing.
- Every People endpoint must exist in one generated registry entry.
- The OpenAPI spec is the source of truth for endpoint coverage.
- Generated code should produce metadata and scaffolding, not unreadable node sprawl.
- Shared factories and overrides must remain small enough to review and maintain manually.
- Every phase must ship both typed operations and tests for the shared factories used in that phase.
- Within each phase, implement in this order:
  1. list/get
  2. create/update/delete
  3. linked resource endpoints
  4. action endpoints

## Phase 0: Foundation and Full Reachability

Goal: make every People endpoint callable from n8n before all typed UX exists.

Scope:

- Parse the OpenAPI spec into a normalized inventory for all People resources and operations.
- Generate the People operation registry from the OpenAPI spec.
- Refactor People execution to a registry-driven dispatcher.
- Add `People API Request`:
  - method
  - path relative to `/people/v2`
  - query params
  - JSON body
- Centralize:
  - pagination
  - query building
  - JSON:API request envelopes
  - response normalization
- Fix current baseline gaps:
  - operation name mismatch for field definition
  - current `limit` behavior that fetches all pages first
  - duplicated create/update field mapping logic
- Add a coverage report that proves registry coverage against the OpenAPI spec.
- Use bundled docs as a secondary validation/reference source where helpful, but not as the primary machine source.

Exit criteria:

- Every documented People endpoint is callable via `People API Request`.
- Registry contains all documented People operations.
- `npm run build` and `npm run lint` pass.
- Coverage check proves `OpenAPI inventory == registry inventory`.

## Phase 1: Core People and Contact Data

Goal: cover the highest-frequency profile automation flows with first-class operations.

Resources and endpoint families in this phase:

- Person root endpoints
- `/me`
- Address
- Email
- PhoneNumber
- Note
- FieldDatum
- Household
- household memberships
- person-scoped contact/note/custom-field endpoints

This phase includes all endpoints under these surfaces, including top-level and person-scoped variants where both exist.

Why first:

- This covers person sync, contact upkeep, household membership, profile enrichment, and basic notes/custom field automation.

Deliverables:

- Full typed CRUD where available.
- Strong Person filter UX using reusable `where[...]` controls.
- Includes and fields support for person-heavy reads.
- Load options for campuses and field definitions where they materially improve UX.

Exit criteria:

- Common person/contact workflows no longer need `People API Request`.
- Person, contact info, note, household, and custom field endpoints are typed and documented.

## Phase 2: Segmentation and Custom Data Administration

Goal: cover list-driven automation and the custom-data model that powers mature People setups.

Resources in this phase:

- List
- ListCategory
- FieldDefinition
- Tab
- Campus
- SchoolOption

Important operations included in this phase:

- list results
- list people
- list rules and conditions
- list shares
- list run
- Mailchimp sync and sync status
- tab field definitions and field options
- campus service times and list relationships

Why second:

- Lists and field definitions are the next major automation layer once person records are manageable from n8n.

Exit criteria:

- Segmentation, custom field schema management, and list execution are fully typed.
- Users can build people sync + list evaluation flows without raw requests.

## Phase 3: Workflows and Follow-Up Automation

Goal: support operational follow-up, assignments, and person progression.

Resources and endpoint families in this phase:

- Workflow
- person workflow cards
- person workflow shares
- NoteCategory
- NoteCategorySubscription
- BackgroundCheck
- SocialProfile

Important actions included in this phase:

- workflow cards create/update/delete
- promote
- skip step
- snooze
- unsnooze
- go back
- remove
- restore
- send email
- workflow shares
- step default assignee
- assignee summaries

Why third:

- These are powerful automations, but they usually follow the core person/list foundation.

Exit criteria:

- Workflow card lifecycle and action endpoints are typed.
- Background checks, social profiles, note categories, and subscriptions are typed.

## Phase 4: Forms, Messaging, Imports, and Reports

Goal: finish the major operational surfaces beyond core records and workflows.

Resources in this phase:

- Form
- FormCategory
- MessageGroup
- Message
- PeopleImport
- Report

Important operations included in this phase:

- form fields
- form field options
- form submissions
- submission values
- message group messages
- message recipients
- people import conflicts and histories
- report CRUD

Why fourth:

- These surfaces are valuable, but they are less universally used than people, lists, and workflows.

Exit criteria:

- Forms, messaging, import monitoring, and report management are fully typed.

## Phase 5: Long-Tail and Read-Only Completeness

Goal: finish the remaining lookup, audit, and reporting endpoints so typed support reaches 100%.

Resources in this phase:

- InactiveReason
- MaritalStatus
- MembershipType
- NamePrefix
- NameSuffix
- App
- Carrier
- SpamEmailAddress
- person_mergers
- BirthdayPeople
- OrganizationStatistics

Why last:

- These are lower-frequency lookup, audit, or reporting endpoints.
- They are still fully reachable from Phase 0 onward via `People API Request`.

Exit criteria:

- Every documented People resource has typed support.
- No People use case requires leaving the node.

## Resource-to-Phase Map

| Resource | Phase | Notes |
|---|---:|---|
| Person | 1 and 3 | Core person/contact endpoints in Phase 1; workflow-card/share and other workflow-linked person endpoints in Phase 3 |
| Address | 1 | Top-level and person-scoped endpoints |
| Email | 1 | Top-level and person-scoped endpoints |
| PhoneNumber | 1 | Top-level and person-scoped endpoints |
| Household | 1 | Includes memberships and person-linked household endpoints |
| FieldDatum | 1 | Person-scoped create plus top-level get/update/delete |
| Note | 1 | Person-scoped create plus top-level get/update/delete |
| List | 2 | Includes run, rules, conditions, shares, people, Mailchimp sync |
| ListCategory | 2 | List organization support |
| FieldDefinition | 2 | Includes field options |
| Tab | 2 | Includes field definitions and field options |
| Campus | 2 | Includes service times and list relationships |
| SchoolOption | 2 | School lookup/admin surface |
| Workflow | 3 | Includes cards, steps, shares, shared people, assignee data |
| NoteCategory | 3 | Includes shares and subscriber/subscription support |
| NoteCategorySubscription | 3 | Subscription-specific endpoints |
| BackgroundCheck | 3 | Top-level and person-scoped endpoints |
| SocialProfile | 3 | Top-level and person-scoped endpoints |
| Form | 4 | Includes fields, options, submissions, submission values |
| FormCategory | 4 | Form organization support |
| MessageGroup | 4 | Includes messages |
| Message | 4 | Includes recipients |
| PeopleImport | 4 | Includes conflicts and histories |
| Report | 4 | Report CRUD |
| InactiveReason | 5 | Lookup/admin |
| MaritalStatus | 5 | Lookup/admin |
| MembershipType | 5 | Lookup/admin |
| NamePrefix | 5 | Lookup/admin |
| NameSuffix | 5 | Lookup/admin |
| App | 5 | Read-only lookup |
| Carrier | 5 | Read-only lookup |
| SpamEmailAddress | 5 | Read-only admin/audit |
| person_mergers | 5 | Read-only merge audit |
| BirthdayPeople | 5 | Read-only reporting |
| OrganizationStatistics | 5 | Read-only reporting |
| default | Excluded | Generator stub, not a real People resource |

## Testing and Verification

- Add a registry coverage test that compares the internal operation manifest to the OpenAPI spec.
- Add unit tests for:
  - path interpolation
  - query serialization
  - pagination
  - JSON:API create/update/action bodies
  - response normalization
- Add representative snapshot tests for generated n8n properties and registry-derived operation groups.
- Add manual smoke checks in n8n for each phase:
  - one get
  - one getMany
  - one create
  - one update
  - one delete-safe flow where possible
  - one action endpoint where applicable
  - one loadOptions case
- Keep `npm run build` and `npm run lint` green at every phase.

## Definition of Done

- All OpenAPI-defined People operations exist in the registry.
- All 502 documented People operations are callable from the node.
- All real People resources have typed entity/operation support.
- Shared query/body/response helpers cover includes, fields, filters, ordering, pagination, and JSON:API envelopes.
- The People surface is documented enough that users can discover operations without reading raw API docs.

## Recommended Implementation Shape

1. Generate a normalized People registry from OpenAPI.
2. Add a spec-driven `People API Request` operation for full endpoint reachability.
3. Build typed entity/operation UX from shared factories backed by the generated registry.
4. Add a small manual override layer for labels, load options, and endpoint quirks.
5. Keep regeneration safe by testing registry coverage against the OpenAPI spec.

## Recommended Delivery Order

1. Phase 0 first, because it guarantees immediate full API reachability.
2. Phase 1 next, because person/contact automation is the highest-usage path.
3. Phase 2 next, because lists and custom fields are the next-most common layer.
4. Phase 3 next, because workflows depend on stable person/list foundations.
5. Phase 4 next, because forms, messaging, imports, and reports are valuable but less universal.
6. Phase 5 last, because it is mostly lookup, audit, and reporting completeness.
