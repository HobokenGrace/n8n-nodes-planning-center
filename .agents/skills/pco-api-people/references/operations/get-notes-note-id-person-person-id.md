# GET /notes/{note_id}/person/{person_id}

**Resource:** [Note](../resources/Note.md)
**Operation ID:** `get--notes-{note_id}-person-{person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_id` | path | string | Yes | The Note id |
| `person_id` | path | string | Yes | The Person id |

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

[note_person_resource_envelope](../schemas/note/note-person-resource-envelope.md)

