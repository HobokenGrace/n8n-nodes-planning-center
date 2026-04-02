# DELETE /field_data/{field_datum_id}/field_definition/{field_definition_id}

**Resource:** [FieldDatum](../resources/FieldDatum.md)
**Operation ID:** `delete--field_data-{field_datum_id}-field_definition-{field_definition_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `field_datum_id` | path | string | Yes | The FieldDatum id |
| `field_definition_id` | path | string | Yes | The FieldDefinition id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

