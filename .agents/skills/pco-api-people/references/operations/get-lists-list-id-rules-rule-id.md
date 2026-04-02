# GET /lists/{list_id}/rules/{rule_id}

**Resource:** [List](../resources/List.md)
**Operation ID:** `get--lists-{list_id}-rules-{rule_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | string | Yes | The List id |
| `rule_id` | path | string | Yes | The Rule id |

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

[list_rules_resource_envelope](../schemas/list/list-rules-resource-envelope.md)

