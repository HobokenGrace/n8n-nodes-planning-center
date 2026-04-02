# DELETE /campuses/{campus_id}/service_times/{service_time_id}

**Resource:** [Campus](../resources/Campus.md)
**Operation ID:** `delete--campuses-{campus_id}-service_times-{service_time_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `campus_id` | path | string | Yes | The Campus id |
| `service_time_id` | path | string | Yes | The ServiceTime id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

