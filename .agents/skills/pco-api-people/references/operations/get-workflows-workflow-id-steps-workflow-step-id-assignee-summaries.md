# GET /workflows/{workflow_id}/steps/{workflow_step_id}/assignee_summaries

**Resource:** [Workflow](../resources/Workflow.md)
**Operation ID:** `get--workflows-{workflow_id}-steps-{workflow_step_id}-assignee_summaries`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_id` | path | string | Yes | The Workflow id |
| `workflow_step_id` | path | string | Yes | The WorkflowStep id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful collection response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[workflow_step_assignee_summaries_collection_envelope](../schemas/workflow/workflow-step-assignee-summaries-collection-envelope.md)

