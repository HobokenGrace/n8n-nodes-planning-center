# PATCH /school_options/{school_option_id}

**Resource:** [SchoolOption](../resources/SchoolOption.md)
**Operation ID:** `patch--school_options-{school_option_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `school_option_id` | path | string | Yes | The SchoolOption id |

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

[organization_school_options_resource_envelope](../schemas/organization/organization-school-options-resource-envelope.md)

