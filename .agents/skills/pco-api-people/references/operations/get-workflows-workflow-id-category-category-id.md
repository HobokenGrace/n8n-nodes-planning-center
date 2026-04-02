# GET /workflows/{workflow_id}/category/{category_id}

**Resource:** [Workflow](../resources/Workflow.md)
**Operation ID:** `get--workflows-{workflow_id}-category-{category_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_id` | path | string | Yes | The Workflow id |
| `category_id` | path | string | Yes | The Category id |

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

[workflow_category_resource_envelope](../schemas/workflow/workflow-category-resource-envelope.md)

