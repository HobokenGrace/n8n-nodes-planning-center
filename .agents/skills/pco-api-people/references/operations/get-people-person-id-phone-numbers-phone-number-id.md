# GET /people/{person_id}/phone_numbers/{phone_number_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}-phone_numbers-{phone_number_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `phone_number_id` | path | string | Yes | The PhoneNumber id |

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

[person_phone_numbers_resource_envelope](../schemas/person/person-phone-numbers-resource-envelope.md)

