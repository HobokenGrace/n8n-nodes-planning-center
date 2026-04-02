# DELETE /workflows/{workflow_id}/cards/{card_id}

**Resource:** [Workflow](../resources/Workflow.md)
**Operation ID:** `delete--workflows-{workflow_id}-cards-{card_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_id` | path | string | Yes | The Workflow id |
| `card_id` | path | string | Yes | The Card id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

