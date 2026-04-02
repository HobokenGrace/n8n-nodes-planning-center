# GET /tabs/{tab_id}

**Resource:** [Tab](../resources/Tab.md)
**Operation ID:** `get--tabs-{tab_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tab_id` | path | string | Yes | The Tab id |

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

[organization_tabs_resource_envelope](../schemas/organization/organization-tabs-resource-envelope.md)

