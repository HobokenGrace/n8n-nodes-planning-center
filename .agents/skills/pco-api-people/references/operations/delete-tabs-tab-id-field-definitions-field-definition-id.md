# DELETE /tabs/{tab_id}/field_definitions/{field_definition_id}

**Resource:** [Tab](../resources/Tab.md)
**Operation ID:** `delete--tabs-{tab_id}-field_definitions-{field_definition_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tab_id` | path | string | Yes | The Tab id |
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

