# DELETE /reports/{report_id}/created_by/{created_by_id}

**Resource:** [Report](../resources/Report.md)
**Operation ID:** `delete--reports-{report_id}-created_by-{created_by_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `report_id` | path | string | Yes | The Report id |
| `created_by_id` | path | string | Yes | The CreatedBy id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

