# GET /reports/{report_id}/created_by

**Resource:** [Report](../resources/Report.md)
**Operation ID:** `get--reports-{report_id}-created_by`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `report_id` | path | string | Yes | The Report id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful collection response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[report_created_by_collection_envelope](../schemas/report/report-created-by-collection-envelope.md)

