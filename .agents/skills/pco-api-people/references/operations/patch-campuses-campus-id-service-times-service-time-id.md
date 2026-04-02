# PATCH /campuses/{campus_id}/service_times/{service_time_id}

**Resource:** [Campus](../resources/Campus.md)
**Operation ID:** `patch--campuses-{campus_id}-service_times-{service_time_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `campus_id` | path | string | Yes | The Campus id |
| `service_time_id` | path | string | Yes | The ServiceTime id |

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

[campus_service_times_resource_envelope](../schemas/campus/campus-service-times-resource-envelope.md)

