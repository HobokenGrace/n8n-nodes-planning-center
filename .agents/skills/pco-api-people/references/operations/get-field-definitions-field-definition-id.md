# GET /field_definitions/{field_definition_id}

**Resource:** [FieldDefinition](../resources/FieldDefinition.md)
**Operation ID:** `get--field_definitions-{field_definition_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `field_definition_id` | path | string | Yes | The FieldDefinition id |

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

[organization_field_definitions_resource_envelope](../schemas/organization/organization-field-definitions-resource-envelope.md)

