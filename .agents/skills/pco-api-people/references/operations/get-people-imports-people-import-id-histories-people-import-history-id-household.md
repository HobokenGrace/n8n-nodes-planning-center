# GET /people_imports/{people_import_id}/histories/{people_import_history_id}/household

**Resource:** [PeopleImport](../resources/PeopleImport.md)
**Operation ID:** `get--people_imports-{people_import_id}-histories-{people_import_history_id}-household`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `people_import_id` | path | string | Yes | The PeopleImport id |
| `people_import_history_id` | path | string | Yes | The PeopleImportHistory id |

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

[people_import_history_household_collection_envelope](../schemas/people/people-import-history-household-collection-envelope.md)

