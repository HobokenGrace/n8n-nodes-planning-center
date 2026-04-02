# GET /emails/{email_id}

**Resource:** [Email](../resources/Email.md)
**Operation ID:** `get--emails-{email_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `email_id` | path | string | Yes | The Email id |

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

[organization_emails_resource_envelope](../schemas/organization/organization-emails-resource-envelope.md)

