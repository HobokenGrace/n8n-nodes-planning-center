# DELETE /emails/{email_id}/person/{person_id}

**Resource:** [Email](../resources/Email.md)
**Operation ID:** `delete--emails-{email_id}-person-{person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `email_id` | path | string | Yes | The Email id |
| `person_id` | path | string | Yes | The Person id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

