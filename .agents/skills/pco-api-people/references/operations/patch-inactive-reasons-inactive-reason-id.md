# PATCH /inactive_reasons/{inactive_reason_id}

**Resource:** [InactiveReason](../resources/InactiveReason.md)
**Operation ID:** `patch--inactive_reasons-{inactive_reason_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `inactive_reason_id` | path | string | Yes | The InactiveReason id |

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

[organization_inactive_reasons_resource_envelope](../schemas/organization/organization-inactive-reasons-resource-envelope.md)

