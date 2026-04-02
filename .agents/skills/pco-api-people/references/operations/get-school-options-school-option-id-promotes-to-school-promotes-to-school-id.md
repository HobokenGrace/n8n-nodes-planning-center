# GET /school_options/{school_option_id}/promotes_to_school/{promotes_to_school_id}

**Resource:** [SchoolOption](../resources/SchoolOption.md)
**Operation ID:** `get--school_options-{school_option_id}-promotes_to_school-{promotes_to_school_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `school_option_id` | path | string | Yes | The SchoolOption id |
| `promotes_to_school_id` | path | string | Yes | The PromotesToSchool id |

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

[school_option_promotes_to_school_resource_envelope](../schemas/school/school-option-promotes-to-school-resource-envelope.md)

