# GET /apps/{app_id}

**Resource:** [App](../resources/App.md)
**Operation ID:** `get--apps-{app_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | string | Yes | The App id |

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

[organization_apps_resource_envelope](../schemas/organization/organization-apps-resource-envelope.md)

