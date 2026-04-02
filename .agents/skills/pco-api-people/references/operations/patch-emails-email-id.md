# PATCH /emails/{email_id}

**Resource:** [Email](../resources/Email.md)
**Operation ID:** `patch--emails-{email_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `email_id` | path | string | Yes | The Email id |

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

[organization_emails_resource_envelope](../schemas/organization/organization-emails-resource-envelope.md)

