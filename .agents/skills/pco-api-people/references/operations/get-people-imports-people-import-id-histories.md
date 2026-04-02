# GET /people_imports/{people_import_id}/histories

**Resource:** [PeopleImport](../resources/PeopleImport.md)
**Operation ID:** `get--people_imports-{people_import_id}-histories`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `people_import_id` | path | string | Yes | The PeopleImport id |

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

[people_import_histories_collection_envelope](../schemas/people/people-import-histories-collection-envelope.md)

