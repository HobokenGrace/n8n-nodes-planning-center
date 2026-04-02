# DELETE /workflows/{workflow_id}/steps/{step_id}/assignee_summaries/{workflow_step_assignee_summary_id}/person/{person_id}

**Resource:** [Workflow](../resources/Workflow.md)
**Operation ID:** `delete--workflows-{workflow_id}-steps-{step_id}-assignee_summaries-{workflow_step_assignee_summary_id}-person-{person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_id` | path | string | Yes | The Workflow id |
| `step_id` | path | string | Yes | The Step id |
| `workflow_step_assignee_summary_id` | path | string | Yes | The WorkflowStepAssigneeSummary id |
| `person_id` | path | string | Yes | The Person id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

