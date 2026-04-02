# DELETE /messages/{message_id}/to/{to_id}

**Resource:** [Message](../resources/Message.md)
**Operation ID:** `delete--messages-{message_id}-to-{to_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `message_id` | path | string | Yes | The Message id |
| `to_id` | path | string | Yes | The To id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

