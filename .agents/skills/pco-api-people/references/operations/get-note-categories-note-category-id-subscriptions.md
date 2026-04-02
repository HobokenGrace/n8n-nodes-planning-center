# GET /note_categories/{note_category_id}/subscriptions

**Resource:** [NoteCategory](../resources/NoteCategory.md)
**Operation ID:** `get--note_categories-{note_category_id}-subscriptions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_category_id` | path | string | Yes | The NoteCategory id |

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

[note_category_subscriptions_collection_envelope](../schemas/note/note-category-subscriptions-collection-envelope.md)

