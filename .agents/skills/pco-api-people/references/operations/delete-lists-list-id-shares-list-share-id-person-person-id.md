# DELETE /lists/{list_id}/shares/{list_share_id}/person/{person_id}

**Resource:** [List](../resources/List.md)
**Operation ID:** `delete--lists-{list_id}-shares-{list_share_id}-person-{person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | string | Yes | The List id |
| `list_share_id` | path | string | Yes | The ListShare id |
| `person_id` | path | string | Yes | The Person id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

