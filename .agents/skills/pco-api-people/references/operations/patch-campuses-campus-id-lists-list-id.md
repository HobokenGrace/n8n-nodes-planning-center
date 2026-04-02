# PATCH /campuses/{campus_id}/lists/{list_id}

**Resource:** [Campus](../resources/Campus.md)
**Operation ID:** `patch--campuses-{campus_id}-lists-{list_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `campus_id` | path | string | Yes | The Campus id |
| `list_id` | path | string | Yes | The List id |

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

[campus_lists_resource_envelope](../schemas/campus/campus-lists-resource-envelope.md)

