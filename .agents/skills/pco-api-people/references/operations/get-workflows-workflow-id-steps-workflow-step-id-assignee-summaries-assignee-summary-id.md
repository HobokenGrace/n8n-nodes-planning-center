# GET /workflows/{workflow_id}/steps/{workflow_step_id}/assignee_summaries/{assignee_summary_id}

**Resource:** [Workflow](../resources/Workflow.md)
**Operation ID:** `get--workflows-{workflow_id}-steps-{workflow_step_id}-assignee_summaries-{assignee_summary_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_id` | path | string | Yes | The Workflow id |
| `workflow_step_id` | path | string | Yes | The WorkflowStep id |
| `assignee_summary_id` | path | string | Yes | The AssigneeSummary id |

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

[workflow_step_assignee_summaries_resource_envelope](../schemas/workflow/workflow-step-assignee-summaries-resource-envelope.md)

