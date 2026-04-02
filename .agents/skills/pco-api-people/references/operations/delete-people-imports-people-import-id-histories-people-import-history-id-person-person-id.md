# DELETE /people_imports/{people_import_id}/histories/{people_import_history_id}/person/{person_id}

**Resource:** [PeopleImport](../resources/PeopleImport.md)
**Operation ID:** `delete--people_imports-{people_import_id}-histories-{people_import_history_id}-person-{person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `people_import_id` | path | string | Yes | The PeopleImport id |
| `people_import_history_id` | path | string | Yes | The PeopleImportHistory id |
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

