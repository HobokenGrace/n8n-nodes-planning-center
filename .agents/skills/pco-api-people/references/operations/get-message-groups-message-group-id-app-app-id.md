# GET /message_groups/{message_group_id}/app/{app_id}

**Resource:** [MessageGroup](../resources/MessageGroup.md)
**Operation ID:** `get--message_groups-{message_group_id}-app-{app_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `message_group_id` | path | string | Yes | The MessageGroup id |
| `app_id` | path | string | Yes | The App id |

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

[message_group_app_resource_envelope](../schemas/message/message-group-app-resource-envelope.md)

