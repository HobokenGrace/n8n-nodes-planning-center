# GET /reports/{report_id}/updated_by/{updated_by_id}

**Resource:** [Report](../resources/Report.md)
**Operation ID:** `get--reports-{report_id}-updated_by-{updated_by_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `report_id` | path | string | Yes | The Report id |
| `updated_by_id` | path | string | Yes | The UpdatedBy id |

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

[report_updated_by_resource_envelope](../schemas/report/report-updated-by-resource-envelope.md)

