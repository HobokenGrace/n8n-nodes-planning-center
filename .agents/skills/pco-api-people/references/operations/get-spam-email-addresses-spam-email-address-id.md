# GET /spam_email_addresses/{spam_email_address_id}

**Resource:** [SpamEmailAddress](../resources/SpamEmailAddress.md)
**Operation ID:** `get--spam_email_addresses-{spam_email_address_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `spam_email_address_id` | path | string | Yes | The SpamEmailAddress id |

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

[organization_spam_email_addresses_resource_envelope](../schemas/organization/organization-spam-email-addresses-resource-envelope.md)

