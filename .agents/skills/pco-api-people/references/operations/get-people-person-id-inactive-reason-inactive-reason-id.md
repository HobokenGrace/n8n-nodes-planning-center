# GET /people/{person_id}/inactive_reason/{inactive_reason_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}-inactive_reason-{inactive_reason_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `inactive_reason_id` | path | string | Yes | The InactiveReason id |

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

[person_inactive_reason_resource_envelope](../schemas/person/person-inactive-reason-resource-envelope.md)

