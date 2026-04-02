# GET /notes/{note_id}/category/{category_id}

**Resource:** [Note](../resources/Note.md)
**Operation ID:** `get--notes-{note_id}-category-{category_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_id` | path | string | Yes | The Note id |
| `category_id` | path | string | Yes | The Category id |

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

[note_category_resource_envelope](../schemas/note/note-category-resource-envelope.md)

