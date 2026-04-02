# GET /people/{person_id}/workflow_cards/{workflow_card_id}/current_step

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}-workflow_cards-{workflow_card_id}-current_step`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `workflow_card_id` | path | string | Yes | The WorkflowCard id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful collection response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[workflow_card_current_step_collection_envelope](../schemas/workflow/workflow-card-current-step-collection-envelope.md)

