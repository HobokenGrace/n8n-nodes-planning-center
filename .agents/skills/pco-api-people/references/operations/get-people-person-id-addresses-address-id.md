# GET /people/{person_id}/addresses/{address_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}-addresses-{address_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `address_id` | path | string | Yes | The Address id |

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

[person_addresses_resource_envelope](../schemas/person/person-addresses-resource-envelope.md)

