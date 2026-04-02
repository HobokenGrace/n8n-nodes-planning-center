# GET /reports/{report_id}

**Resource:** [Report](../resources/Report.md)
**Operation ID:** `get--reports-{report_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `report_id` | path | string | Yes | The Report id |

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

[organization_reports_resource_envelope](../schemas/organization/organization-reports-resource-envelope.md)

