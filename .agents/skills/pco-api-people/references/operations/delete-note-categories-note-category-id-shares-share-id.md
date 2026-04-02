# DELETE /note_categories/{note_category_id}/shares/{share_id}

**Resource:** [NoteCategory](../resources/NoteCategory.md)
**Operation ID:** `delete--note_categories-{note_category_id}-shares-{share_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_category_id` | path | string | Yes | The NoteCategory id |
| `share_id` | path | string | Yes | The Share id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

