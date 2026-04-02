# GET /workflows/{workflow_id}/steps/{workflow_step_id}/default_assignee/{default_assignee_id}

**Resource:** [Workflow](../resources/Workflow.md)
**Operation ID:** `get--workflows-{workflow_id}-steps-{workflow_step_id}-default_assignee-{default_assignee_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_id` | path | string | Yes | The Workflow id |
| `workflow_step_id` | path | string | Yes | The WorkflowStep id |
| `default_assignee_id` | path | string | Yes | The DefaultAssignee id |

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

[workflow_step_default_assignee_resource_envelope](../schemas/workflow/workflow-step-default-assignee-resource-envelope.md)

