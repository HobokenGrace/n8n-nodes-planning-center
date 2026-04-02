# PATCH /field_data/{field_datum_id}/field_option/{field_option_id}

**Resource:** [FieldDatum](../resources/FieldDatum.md)
**Operation ID:** `patch--field_data-{field_datum_id}-field_option-{field_option_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `field_datum_id` | path | string | Yes | The FieldDatum id |
| `field_option_id` | path | string | Yes | The FieldOption id |

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

[field_datum_field_option_resource_envelope](../schemas/field/field-datum-field-option-resource-envelope.md)

