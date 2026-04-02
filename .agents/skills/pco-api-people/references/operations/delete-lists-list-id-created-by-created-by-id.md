# DELETE /lists/{list_id}/created_by/{created_by_id}

**Resource:** [List](../resources/List.md)
**Operation ID:** `delete--lists-{list_id}-created_by-{created_by_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | string | Yes | The List id |
| `created_by_id` | path | string | Yes | The CreatedBy id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

