# POST /people/{person_id}/field_data

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `post--people-{person_id}-field_data`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successful create response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[person_field_data_resource_envelope](../schemas/person/person-field-data-resource-envelope.md)

