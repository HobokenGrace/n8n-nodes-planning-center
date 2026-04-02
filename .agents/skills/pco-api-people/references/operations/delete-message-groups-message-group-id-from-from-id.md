# DELETE /message_groups/{message_group_id}/from/{from_id}

**Resource:** [MessageGroup](../resources/MessageGroup.md)
**Operation ID:** `delete--message_groups-{message_group_id}-from-{from_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `message_group_id` | path | string | Yes | The MessageGroup id |
| `from_id` | path | string | Yes | The From id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

