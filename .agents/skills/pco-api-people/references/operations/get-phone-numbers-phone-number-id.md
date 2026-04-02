# GET /phone_numbers/{phone_number_id}

**Resource:** [PhoneNumber](../resources/PhoneNumber.md)
**Operation ID:** `get--phone_numbers-{phone_number_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

[organization_phone_numbers_resource_envelope](../schemas/organization/organization-phone-numbers-resource-envelope.md)

