# GET /note_categories/{note_category_id}

**Resource:** [NoteCategory](../resources/NoteCategory.md)
**Operation ID:** `get--note_categories-{note_category_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_category_id` | path | string | Yes | The NoteCategory id |

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

[organization_note_categories_resource_envelope](../schemas/organization/organization-note-categories-resource-envelope.md)

