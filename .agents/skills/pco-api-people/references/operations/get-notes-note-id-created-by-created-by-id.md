# GET /notes/{note_id}/created_by/{created_by_id}

**Resource:** [Note](../resources/Note.md)
**Operation ID:** `get--notes-{note_id}-created_by-{created_by_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_id` | path | string | Yes | The Note id |
| `created_by_id` | path | string | Yes | The CreatedBy id |

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

[note_created_by_resource_envelope](../schemas/note/note-created-by-resource-envelope.md)

