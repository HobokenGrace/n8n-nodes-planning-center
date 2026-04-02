# POST /campuses/{campus_id}/service_times

**Resource:** [Campus](../resources/Campus.md)
**Operation ID:** `post--campuses-{campus_id}-service_times`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `campus_id` | path | string | Yes | The Campus id |

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

[campus_service_times_resource_envelope](../schemas/campus/campus-service-times-resource-envelope.md)

