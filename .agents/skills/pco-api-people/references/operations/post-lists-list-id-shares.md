# POST /lists/{list_id}/shares

**Resource:** [List](../resources/List.md)
**Operation ID:** `post--lists-{list_id}-shares`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | string | Yes | The List id |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successful create response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[list_shares_resource_envelope](../schemas/list/list-shares-resource-envelope.md)

