# GET /messages/{message_id}/to

**Resource:** [Message](../resources/Message.md)
**Operation ID:** `get--messages-{message_id}-to`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `message_id` | path | string | Yes | The Message id |

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

[message_to_collection_envelope](../schemas/message/message-to-collection-envelope.md)

