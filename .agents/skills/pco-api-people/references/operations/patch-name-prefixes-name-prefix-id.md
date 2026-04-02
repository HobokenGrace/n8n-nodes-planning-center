# PATCH /name_prefixes/{name_prefix_id}

**Resource:** [NamePrefix](../resources/NamePrefix.md)
**Operation ID:** `patch--name_prefixes-{name_prefix_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name_prefix_id` | path | string | Yes | The NamePrefix id |

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

[organization_name_prefixes_resource_envelope](../schemas/organization/organization-name-prefixes-resource-envelope.md)

