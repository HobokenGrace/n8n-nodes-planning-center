# GET /note_categories/{note_category_id}/subscriptions/{subscription_id}

**Resource:** [NoteCategory](../resources/NoteCategory.md)
**Operation ID:** `get--note_categories-{note_category_id}-subscriptions-{subscription_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_category_id` | path | string | Yes | The NoteCategory id |
| `subscription_id` | path | string | Yes | The Subscription id |

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

[note_category_subscriptions_resource_envelope](../schemas/note/note-category-subscriptions-resource-envelope.md)

