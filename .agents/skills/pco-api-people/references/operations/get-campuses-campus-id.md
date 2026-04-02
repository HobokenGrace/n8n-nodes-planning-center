# GET /campuses/{campus_id}

**Resource:** [Campus](../resources/Campus.md)
**Operation ID:** `get--campuses-{campus_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `campus_id` | path | string | Yes | The Campus id |

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

[organization_campuses_resource_envelope](../schemas/organization/organization-campuses-resource-envelope.md)

