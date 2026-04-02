# GET /workflows/{workflow_id}/category

**Resource:** [Workflow](../resources/Workflow.md)
**Operation ID:** `get--workflows-{workflow_id}-category`

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

[workflow_category_collection_envelope](../schemas/workflow/workflow-category-collection-envelope.md)

