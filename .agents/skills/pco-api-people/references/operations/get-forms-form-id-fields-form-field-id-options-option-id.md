# GET /forms/{form_id}/fields/{form_field_id}/options/{option_id}

**Resource:** [Form](../resources/Form.md)
**Operation ID:** `get--forms-{form_id}-fields-{form_field_id}-options-{option_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `form_id` | path | string | Yes | The Form id |
| `form_field_id` | path | string | Yes | The FormField id |
| `option_id` | path | string | Yes | The Option id |

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

[form_field_options_resource_envelope](../schemas/form/form-field-options-resource-envelope.md)

