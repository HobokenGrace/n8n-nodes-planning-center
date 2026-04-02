# DELETE /people/{person_id}/school/{school_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `delete--people-{person_id}-school-{school_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `school_id` | path | string | Yes | The School id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

