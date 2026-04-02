# GET /people/{person_id}/platform_notifications/{platform_notification_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}-platform_notifications-{platform_notification_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `platform_notification_id` | path | string | Yes | The PlatformNotification id |

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

[person_platform_notifications_resource_envelope](../schemas/person/person-platform-notifications-resource-envelope.md)

