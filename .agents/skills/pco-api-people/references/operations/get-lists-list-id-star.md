# GET /lists/{list_id}/star

**Resource:** [List](../resources/List.md)
**Operation ID:** `get--lists-{list_id}-star`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | string | Yes | The List id |

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

[list_star_resource_envelope](../schemas/list/list-star-resource-envelope.md)

