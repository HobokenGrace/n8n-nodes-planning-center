# PATCH /field_definitions/{field_definition_id}/tab/{tab_id}

**Resource:** [FieldDefinition](../resources/FieldDefinition.md)
**Operation ID:** `patch--field_definitions-{field_definition_id}-tab-{tab_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `field_definition_id` | path | string | Yes | The FieldDefinition id |
| `tab_id` | path | string | Yes | The Tab id |

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

[field_definition_tab_resource_envelope](../schemas/field/field-definition-tab-resource-envelope.md)

