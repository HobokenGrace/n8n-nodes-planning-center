# GET /lists/{list_id}/created_by/{created_by_id}

**Resource:** [List](../resources/List.md)
**Operation ID:** `get--lists-{list_id}-created_by-{created_by_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | string | Yes | The List id |
| `created_by_id` | path | string | Yes | The CreatedBy id |

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

[list_created_by_resource_envelope](../schemas/list/list-created-by-resource-envelope.md)

