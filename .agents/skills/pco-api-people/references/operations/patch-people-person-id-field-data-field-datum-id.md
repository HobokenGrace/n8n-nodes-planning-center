# PATCH /people/{person_id}/field_data/{field_datum_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `patch--people-{person_id}-field_data-{field_datum_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `field_datum_id` | path | string | Yes | The FieldDatum id |

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

[person_field_data_resource_envelope](../schemas/person/person-field-data-resource-envelope.md)

