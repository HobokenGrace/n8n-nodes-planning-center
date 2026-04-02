# GET /lists/{list_id}/category

**Resource:** [List](../resources/List.md)
**Operation ID:** `get--lists-{list_id}-category`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | string | Yes | The List id |

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

[list_category_collection_envelope](../schemas/list/list-category-collection-envelope.md)

