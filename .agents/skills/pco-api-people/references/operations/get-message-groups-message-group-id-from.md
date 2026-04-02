# GET /message_groups/{message_group_id}/from

**Resource:** [MessageGroup](../resources/MessageGroup.md)
**Operation ID:** `get--message_groups-{message_group_id}-from`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `message_group_id` | path | string | Yes | The MessageGroup id |

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

[message_group_from_collection_envelope](../schemas/message/message-group-from-collection-envelope.md)

