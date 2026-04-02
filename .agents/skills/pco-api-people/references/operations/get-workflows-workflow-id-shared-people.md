# GET /workflows/{workflow_id}/shared_people

**Resource:** [Workflow](../resources/Workflow.md)
**Operation ID:** `get--workflows-{workflow_id}-shared_people`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_id` | path | string | Yes | The Workflow id |

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

[workflow_shared_people_collection_envelope](../schemas/workflow/workflow-shared-people-collection-envelope.md)

