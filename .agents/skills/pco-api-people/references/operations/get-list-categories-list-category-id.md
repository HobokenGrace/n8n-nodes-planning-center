# GET /list_categories/{list_category_id}

**Resource:** [ListCategory](../resources/ListCategory.md)
**Operation ID:** `get--list_categories-{list_category_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_category_id` | path | string | Yes | The ListCategory id |

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

[organization_list_categories_resource_envelope](../schemas/organization/organization-list-categories-resource-envelope.md)

