# PATCH /lists/{list_id}

**Resource:** [List](../resources/List.md)
**Operation ID:** `patch--lists-{list_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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

[organization_lists_resource_envelope](../schemas/organization/organization-lists-resource-envelope.md)

