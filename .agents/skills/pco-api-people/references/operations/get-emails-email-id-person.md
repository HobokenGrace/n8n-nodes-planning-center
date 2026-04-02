# GET /emails/{email_id}/person

**Resource:** [Email](../resources/Email.md)
**Operation ID:** `get--emails-{email_id}-person`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `email_id` | path | string | Yes | The Email id |

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

[email_person_collection_envelope](../schemas/email/email-person-collection-envelope.md)

