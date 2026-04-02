# DELETE /lists/{list_id}/category/{category_id}

**Resource:** [List](../resources/List.md)
**Operation ID:** `delete--lists-{list_id}-category-{category_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | string | Yes | The List id |
| `category_id` | path | string | Yes | The Category id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

