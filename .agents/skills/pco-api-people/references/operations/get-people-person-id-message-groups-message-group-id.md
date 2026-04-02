# GET /people/{person_id}/message_groups/{message_group_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}-message_groups-{message_group_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
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

[person_message_groups_resource_envelope](../schemas/person/person-message-groups-resource-envelope.md)

