# Message

A message is an individual email or sms text sent to a member. Every message has a parent message group.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/messages` |  | [View](../operations/get-messages.md) |
| GET | `/messages/{message_id}` |  | [View](../operations/get-messages-message-id.md) |
| GET | `/messages/{message_id}/message_group` |  | [View](../operations/get-messages-message-id-message-group.md) |
| GET | `/messages/{message_id}/message_group/{message_group_id}` |  | [View](../operations/get-messages-message-id-message-group-message-group-id.md) |
| GET | `/messages/{message_id}/to` |  | [View](../operations/get-messages-message-id-to.md) |
| GET | `/messages/{message_id}/to/{to_id}` |  | [View](../operations/get-messages-message-id-to-to-id.md) |
| DELETE | `/messages/{message_id}/to/{to_id}` |  | [View](../operations/delete-messages-message-id-to-to-id.md) |
| PATCH | `/messages/{message_id}/to/{to_id}` |  | [View](../operations/patch-messages-message-id-to-to-id.md) |
