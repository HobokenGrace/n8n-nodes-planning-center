# GET /notes/{note_id}/person

**Resource:** [Note](../resources/Note.md)
**Operation ID:** `get--notes-{note_id}-person`

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

[note_person_collection_envelope](../schemas/note/note-person-collection-envelope.md)

