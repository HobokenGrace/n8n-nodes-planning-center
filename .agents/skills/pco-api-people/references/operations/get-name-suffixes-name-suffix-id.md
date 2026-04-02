# GET /name_suffixes/{name_suffix_id}

**Resource:** [NameSuffix](../resources/NameSuffix.md)
**Operation ID:** `get--name_suffixes-{name_suffix_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name_suffix_id` | path | string | Yes | The NameSuffix id |

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

[organization_name_suffixes_resource_envelope](../schemas/organization/organization-name-suffixes-resource-envelope.md)

