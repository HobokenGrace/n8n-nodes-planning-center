# GET /lists/{list_id}/updated_by/{updated_by_id}

**Resource:** [List](../resources/List.md)
**Operation ID:** `get--lists-{list_id}-updated_by-{updated_by_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | string | Yes | The List id |
| `updated_by_id` | path | string | Yes | The UpdatedBy id |

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

[list_updated_by_resource_envelope](../schemas/list/list-updated-by-resource-envelope.md)

