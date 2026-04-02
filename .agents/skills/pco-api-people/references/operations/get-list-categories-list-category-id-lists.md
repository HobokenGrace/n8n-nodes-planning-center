# GET /list_categories/{list_category_id}/lists

**Resource:** [ListCategory](../resources/ListCategory.md)
**Operation ID:** `get--list_categories-{list_category_id}-lists`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_category_id` | path | string | Yes | The ListCategory id |

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

[list_category_lists_collection_envelope](../schemas/list/list-category-lists-collection-envelope.md)

