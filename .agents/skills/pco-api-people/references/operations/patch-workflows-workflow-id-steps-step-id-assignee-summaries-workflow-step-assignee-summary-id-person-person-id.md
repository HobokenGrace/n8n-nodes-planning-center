# PATCH /workflows/{workflow_id}/steps/{step_id}/assignee_summaries/{workflow_step_assignee_summary_id}/person/{person_id}

**Resource:** [Workflow](../resources/Workflow.md)
**Operation ID:** `patch--workflows-{workflow_id}-steps-{step_id}-assignee_summaries-{workflow_step_assignee_summary_id}-person-{person_id}`

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
| 200 | Successful update response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[workflow_step_assignee_summary_person_resource_envelope](../schemas/workflow/workflow-step-assignee-summary-person-resource-envelope.md)

