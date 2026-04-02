# PATCH /tabs/{tab_id}/field_definitions/{field_definition_id}

**Resource:** [Tab](../resources/Tab.md)
**Operation ID:** `patch--tabs-{tab_id}-field_definitions-{field_definition_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tab_id` | path | string | Yes | The Tab id |
| `field_definition_id` | path | string | Yes | The FieldDefinition id |

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

[tab_field_definitions_resource_envelope](../schemas/tab/tab-field-definitions-resource-envelope.md)

