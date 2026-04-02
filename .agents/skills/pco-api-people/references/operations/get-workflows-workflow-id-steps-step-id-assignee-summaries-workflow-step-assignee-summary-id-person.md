# GET /workflows/{workflow_id}/steps/{step_id}/assignee_summaries/{workflow_step_assignee_summary_id}/person

**Resource:** [Workflow](../resources/Workflow.md)
**Operation ID:** `get--workflows-{workflow_id}-steps-{step_id}-assignee_summaries-{workflow_step_assignee_summary_id}-person`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_id` | path | string | Yes | The Workflow id |
| `step_id` | path | string | Yes | The Step id |
| `workflow_step_assignee_summary_id` | path | string | Yes | The WorkflowStepAssigneeSummary id |

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

[workflow_step_assignee_summary_person_collection_envelope](../schemas/workflow/workflow-step-assignee-summary-person-collection-envelope.md)

