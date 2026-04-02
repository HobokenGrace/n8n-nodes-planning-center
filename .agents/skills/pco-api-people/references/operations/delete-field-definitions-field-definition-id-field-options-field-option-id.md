# DELETE /field_definitions/{field_definition_id}/field_options/{field_option_id}

**Resource:** [FieldDefinition](../resources/FieldDefinition.md)
**Operation ID:** `delete--field_definitions-{field_definition_id}-field_options-{field_option_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `field_definition_id` | path | string | Yes | The FieldDefinition id |
| `field_option_id` | path | string | Yes | The FieldOption id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

