# PATCH /form_categories/{form_category_id}

**Resource:** [FormCategory](../resources/FormCategory.md)
**Operation ID:** `patch--form_categories-{form_category_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `form_category_id` | path | string | Yes | The FormCategory id |

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

[organization_form_categories_resource_envelope](../schemas/organization/organization-form-categories-resource-envelope.md)

