# PATCH /messages/{message_id}/to/{to_id}

**Resource:** [Message](../resources/Message.md)
**Operation ID:** `patch--messages-{message_id}-to-{to_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `message_id` | path | string | Yes | The Message id |
| `to_id` | path | string | Yes | The To id |

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

[message_to_resource_envelope](../schemas/message/message-to-resource-envelope.md)

