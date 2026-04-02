# GET /people_imports/{people_import_id}/conflicts/{conflict_id}

**Resource:** [PeopleImport](../resources/PeopleImport.md)
**Operation ID:** `get--people_imports-{people_import_id}-conflicts-{conflict_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `people_import_id` | path | string | Yes | The PeopleImport id |
| `conflict_id` | path | string | Yes | The Conflict id |

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

[people_import_conflicts_resource_envelope](../schemas/people/people-import-conflicts-resource-envelope.md)

