# PATCH /reports/{report_id}

**Resource:** [Report](../resources/Report.md)
**Operation ID:** `patch--reports-{report_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `report_id` | path | string | Yes | The Report id |

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

[organization_reports_resource_envelope](../schemas/organization/organization-reports-resource-envelope.md)

