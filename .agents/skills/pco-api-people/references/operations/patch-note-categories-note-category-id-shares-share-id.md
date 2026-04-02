# PATCH /note_categories/{note_category_id}/shares/{share_id}

**Resource:** [NoteCategory](../resources/NoteCategory.md)
**Operation ID:** `patch--note_categories-{note_category_id}-shares-{share_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_category_id` | path | string | Yes | The NoteCategory id |
| `share_id` | path | string | Yes | The Share id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful update response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[note_category_shares_resource_envelope](../schemas/note/note-category-shares-resource-envelope.md)

