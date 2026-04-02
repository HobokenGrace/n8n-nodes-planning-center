# GET /person_mergers/{person_merger_id}

**Resource:** [person_mergers](../resources/person-mergers.md)
**Operation ID:** `get--person_mergers-{person_merger_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_merger_id` | path | string | Yes | The PersonMerger id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful read response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[organization_person_mergers_resource_envelope](../schemas/organization/organization-person-mergers-resource-envelope.md)

