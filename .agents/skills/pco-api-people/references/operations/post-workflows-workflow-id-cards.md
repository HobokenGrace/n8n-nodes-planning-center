# POST /workflows/{workflow_id}/cards

**Resource:** [Workflow](../resources/Workflow.md)
**Operation ID:** `post--workflows-{workflow_id}-cards`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_id` | path | string | Yes | The Workflow id |

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

[workflow_cards_resource_envelope](../schemas/workflow/workflow-cards-resource-envelope.md)

