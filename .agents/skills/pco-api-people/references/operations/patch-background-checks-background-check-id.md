# PATCH /background_checks/{background_check_id}

**Resource:** [BackgroundCheck](../resources/BackgroundCheck.md)
**Operation ID:** `patch--background_checks-{background_check_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `background_check_id` | path | string | Yes | The BackgroundCheck id |

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

[organization_background_checks_resource_envelope](../schemas/organization/organization-background-checks-resource-envelope.md)

