# DELETE /people/{person_id}/inactive_reason/{inactive_reason_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `delete--people-{person_id}-inactive_reason-{inactive_reason_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `inactive_reason_id` | path | string | Yes | The InactiveReason id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

