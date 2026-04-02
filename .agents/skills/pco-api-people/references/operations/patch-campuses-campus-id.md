# PATCH /campuses/{campus_id}

**Resource:** [Campus](../resources/Campus.md)
**Operation ID:** `patch--campuses-{campus_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `campus_id` | path | string | Yes | The Campus id |

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

[organization_campuses_resource_envelope](../schemas/organization/organization-campuses-resource-envelope.md)

