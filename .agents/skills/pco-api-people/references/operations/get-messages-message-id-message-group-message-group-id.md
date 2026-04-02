# GET /messages/{message_id}/message_group/{message_group_id}

**Resource:** [Message](../resources/Message.md)
**Operation ID:** `get--messages-{message_id}-message_group-{message_group_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `message_id` | path | string | Yes | The Message id |
| `message_group_id` | path | string | Yes | The MessageGroup id |

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

[message_message_group_resource_envelope](../schemas/message/message-message-group-resource-envelope.md)

