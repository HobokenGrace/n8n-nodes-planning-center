# DELETE /note_categories/{note_category_id}/shares/{note_category_share_id}/person/{person_id}

**Resource:** [NoteCategory](../resources/NoteCategory.md)
**Operation ID:** `delete--note_categories-{note_category_id}-shares-{note_category_share_id}-person-{person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_category_id` | path | string | Yes | The NoteCategory id |
| `note_category_share_id` | path | string | Yes | The NoteCategoryShare id |
| `person_id` | path | string | Yes | The Person id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

