# GET /people_imports/{people_import_id}/histories/{history_id}

**Resource:** [PeopleImport](../resources/PeopleImport.md)
**Operation ID:** `get--people_imports-{people_import_id}-histories-{history_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `people_import_id` | path | string | Yes | The PeopleImport id |
| `history_id` | path | string | Yes | The History id |

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

[people_import_histories_resource_envelope](../schemas/people/people-import-histories-resource-envelope.md)

