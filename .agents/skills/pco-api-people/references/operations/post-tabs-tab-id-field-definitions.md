# POST /tabs/{tab_id}/field_definitions

**Resource:** [Tab](../resources/Tab.md)
**Operation ID:** `post--tabs-{tab_id}-field_definitions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tab_id` | path | string | Yes | The Tab id |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successful create response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[tab_field_definitions_resource_envelope](../schemas/tab/tab-field-definitions-resource-envelope.md)

