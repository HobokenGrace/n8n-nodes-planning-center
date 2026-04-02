# GET /notes/{note_id}/created_by

**Resource:** [Note](../resources/Note.md)
**Operation ID:** `get--notes-{note_id}-created_by`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_id` | path | string | Yes | The Note id |

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

[note_created_by_collection_envelope](../schemas/note/note-created-by-collection-envelope.md)

