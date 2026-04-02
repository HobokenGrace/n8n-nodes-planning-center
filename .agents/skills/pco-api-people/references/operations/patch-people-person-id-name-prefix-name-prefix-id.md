# PATCH /people/{person_id}/name_prefix/{name_prefix_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `patch--people-{person_id}-name_prefix-{name_prefix_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `name_prefix_id` | path | string | Yes | The NamePrefix id |

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

[person_name_prefix_resource_envelope](../schemas/person/person-name-prefix-resource-envelope.md)

