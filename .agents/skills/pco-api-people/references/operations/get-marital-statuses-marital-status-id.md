# GET /marital_statuses/{marital_status_id}

**Resource:** [MaritalStatus](../resources/MaritalStatus.md)
**Operation ID:** `get--marital_statuses-{marital_status_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `marital_status_id` | path | string | Yes | The MaritalStatus id |

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

[organization_marital_statuses_resource_envelope](../schemas/organization/organization-marital-statuses-resource-envelope.md)

