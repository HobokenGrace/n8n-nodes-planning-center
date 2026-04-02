# GET /addresses/{address_id}

**Resource:** [Address](../resources/Address.md)
**Operation ID:** `get--addresses-{address_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

[organization_addresses_resource_envelope](../schemas/organization/organization-addresses-resource-envelope.md)

