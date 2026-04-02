# GET /field_data/{field_datum_id}/person

**Resource:** [FieldDatum](../resources/FieldDatum.md)
**Operation ID:** `get--field_data-{field_datum_id}-person`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `field_datum_id` | path | string | Yes | The FieldDatum id |

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

[field_datum_person_collection_envelope](../schemas/field/field-datum-person-collection-envelope.md)

