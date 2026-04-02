# GET /forms/{form_id}/category/{category_id}

**Resource:** [Form](../resources/Form.md)
**Operation ID:** `get--forms-{form_id}-category-{category_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `form_id` | path | string | Yes | The Form id |
| `category_id` | path | string | Yes | The Category id |

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

[form_category_resource_envelope](../schemas/form/form-category-resource-envelope.md)

