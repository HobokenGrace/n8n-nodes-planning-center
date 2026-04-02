# PATCH /tabs/{tab_id}/field_options/{field_option_id}

**Resource:** [Tab](../resources/Tab.md)
**Operation ID:** `patch--tabs-{tab_id}-field_options-{field_option_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tab_id` | path | string | Yes | The Tab id |
| `field_option_id` | path | string | Yes | The FieldOption id |

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

[tab_field_options_resource_envelope](../schemas/tab/tab-field-options-resource-envelope.md)

