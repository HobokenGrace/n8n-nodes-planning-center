# GET /school_options/{school_option_id}/promotes_to_school

**Resource:** [SchoolOption](../resources/SchoolOption.md)
**Operation ID:** `get--school_options-{school_option_id}-promotes_to_school`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `school_option_id` | path | string | Yes | The SchoolOption id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful collection response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[school_option_promotes_to_school_collection_envelope](../schemas/school/school-option-promotes-to-school-collection-envelope.md)

