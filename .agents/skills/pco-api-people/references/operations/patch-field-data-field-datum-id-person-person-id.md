# PATCH /field_data/{field_datum_id}/person/{person_id}

**Resource:** [FieldDatum](../resources/FieldDatum.md)
**Operation ID:** `patch--field_data-{field_datum_id}-person-{person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `field_datum_id` | path | string | Yes | The FieldDatum id |
| `person_id` | path | string | Yes | The Person id |

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

[field_datum_person_resource_envelope](../schemas/field/field-datum-person-resource-envelope.md)

