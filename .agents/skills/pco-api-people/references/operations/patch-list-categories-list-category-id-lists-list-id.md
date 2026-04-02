# PATCH /list_categories/{list_category_id}/lists/{list_id}

**Resource:** [ListCategory](../resources/ListCategory.md)
**Operation ID:** `patch--list_categories-{list_category_id}-lists-{list_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_category_id` | path | string | Yes | The ListCategory id |
| `list_id` | path | string | Yes | The List id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful update response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[list_category_lists_resource_envelope](../schemas/list/list-category-lists-resource-envelope.md)

