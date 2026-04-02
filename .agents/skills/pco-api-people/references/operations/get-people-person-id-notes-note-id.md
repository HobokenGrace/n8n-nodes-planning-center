# GET /people/{person_id}/notes/{note_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}-notes-{note_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `note_id` | path | string | Yes | The Note id |

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

[person_notes_resource_envelope](../schemas/person/person-notes-resource-envelope.md)

