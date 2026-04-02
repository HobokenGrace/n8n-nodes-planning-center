# GET /people/{person_id}/name_prefix

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}-name_prefix`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |

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

[person_name_prefix_collection_envelope](../schemas/person/person-name-prefix-collection-envelope.md)

