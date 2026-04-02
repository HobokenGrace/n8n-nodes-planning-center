# GET /note_categories/{note_category_id}/shares/{note_category_share_id}/person

**Resource:** [NoteCategory](../resources/NoteCategory.md)
**Operation ID:** `get--note_categories-{note_category_id}-shares-{note_category_share_id}-person`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_category_id` | path | string | Yes | The NoteCategory id |
| `note_category_share_id` | path | string | Yes | The NoteCategoryShare id |

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

[note_category_share_person_collection_envelope](../schemas/note/note-category-share-person-collection-envelope.md)

