# GET /tabs/{tab_id}/field_definitions

**Resource:** [Tab](../resources/Tab.md)
**Operation ID:** `get--tabs-{tab_id}-field_definitions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tab_id` | path | string | Yes | The Tab id |

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

[tab_field_definitions_collection_envelope](../schemas/tab/tab-field-definitions-collection-envelope.md)

