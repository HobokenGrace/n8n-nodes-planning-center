# PATCH /field_definitions/{field_definition_id}/field_options/{field_option_id}

**Resource:** [FieldDefinition](../resources/FieldDefinition.md)
**Operation ID:** `patch--field_definitions-{field_definition_id}-field_options-{field_option_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `field_definition_id` | path | string | Yes | The FieldDefinition id |
| `field_option_id` | path | string | Yes | The FieldOption id |

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

[field_definition_field_options_resource_envelope](../schemas/field/field-definition-field-options-resource-envelope.md)

