# GET /people/{person_id}/person_apps/{person_app_id}/app

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}-person_apps-{person_app_id}-app`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `person_app_id` | path | string | Yes | The PersonApp id |

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

[person_app_app_collection_envelope](../schemas/person/person-app-app-collection-envelope.md)

