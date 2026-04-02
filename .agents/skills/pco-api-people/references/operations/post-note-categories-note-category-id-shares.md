# POST /note_categories/{note_category_id}/shares

**Resource:** [NoteCategory](../resources/NoteCategory.md)
**Operation ID:** `post--note_categories-{note_category_id}-shares`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_category_id` | path | string | Yes | The NoteCategory id |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successful create response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[note_category_shares_resource_envelope](../schemas/note/note-category-shares-resource-envelope.md)

