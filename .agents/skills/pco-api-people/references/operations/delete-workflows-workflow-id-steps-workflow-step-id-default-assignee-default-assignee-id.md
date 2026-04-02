# DELETE /workflows/{workflow_id}/steps/{workflow_step_id}/default_assignee/{default_assignee_id}

**Resource:** [Workflow](../resources/Workflow.md)
**Operation ID:** `delete--workflows-{workflow_id}-steps-{workflow_step_id}-default_assignee-{default_assignee_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_id` | path | string | Yes | The Workflow id |
| `workflow_step_id` | path | string | Yes | The WorkflowStep id |
| `default_assignee_id` | path | string | Yes | The DefaultAssignee id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

