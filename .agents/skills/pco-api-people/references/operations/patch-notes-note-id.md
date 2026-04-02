# PATCH /notes/{note_id}

**Resource:** [Note](../resources/Note.md)
**Operation ID:** `patch--notes-{note_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_id` | path | string | Yes | The Note id |

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

[organization_notes_resource_envelope](../schemas/organization/organization-notes-resource-envelope.md)

