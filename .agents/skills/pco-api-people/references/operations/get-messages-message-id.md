# GET /messages/{message_id}

**Resource:** [Message](../resources/Message.md)
**Operation ID:** `get--messages-{message_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `message_id` | path | string | Yes | The Message id |

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

[organization_messages_resource_envelope](../schemas/organization/organization-messages-resource-envelope.md)

