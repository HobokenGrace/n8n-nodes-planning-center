# GET /reports/{report_id}/created_by/{created_by_id}

**Resource:** [Report](../resources/Report.md)
**Operation ID:** `get--reports-{report_id}-created_by-{created_by_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `report_id` | path | string | Yes | The Report id |
| `created_by_id` | path | string | Yes | The CreatedBy id |

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

[report_created_by_resource_envelope](../schemas/report/report-created-by-resource-envelope.md)

