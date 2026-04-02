# PATCH /workflows/{workflow_id}/shared_people/{shared_person_id}

**Resource:** [Workflow](../resources/Workflow.md)
**Operation ID:** `patch--workflows-{workflow_id}-shared_people-{shared_person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_id` | path | string | Yes | The Workflow id |
| `shared_person_id` | path | string | Yes | The SharedPerson id |

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

[workflow_shared_people_resource_envelope](../schemas/workflow/workflow-shared-people-resource-envelope.md)

