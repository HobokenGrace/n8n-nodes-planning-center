# GET /field_data/{field_datum_id}

**Resource:** [FieldDatum](../resources/FieldDatum.md)
**Operation ID:** `get--field_data-{field_datum_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `field_datum_id` | path | string | Yes | The FieldDatum id |

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

[organization_field_data_resource_envelope](../schemas/organization/organization-field-data-resource-envelope.md)

