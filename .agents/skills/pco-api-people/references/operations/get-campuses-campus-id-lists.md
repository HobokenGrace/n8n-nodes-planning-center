# GET /campuses/{campus_id}/lists

**Resource:** [Campus](../resources/Campus.md)
**Operation ID:** `get--campuses-{campus_id}-lists`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `campus_id` | path | string | Yes | The Campus id |

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

[campus_lists_collection_envelope](../schemas/campus/campus-lists-collection-envelope.md)

