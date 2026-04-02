# GET /field_definitions/{field_definition_id}/tab

**Resource:** [FieldDefinition](../resources/FieldDefinition.md)
**Operation ID:** `get--field_definitions-{field_definition_id}-tab`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `field_definition_id` | path | string | Yes | The FieldDefinition id |

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

[field_definition_tab_collection_envelope](../schemas/field/field-definition-tab-collection-envelope.md)

