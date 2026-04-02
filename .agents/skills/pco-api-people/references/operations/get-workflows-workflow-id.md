# GET /workflows/{workflow_id}

**Resource:** [Workflow](../resources/Workflow.md)
**Operation ID:** `get--workflows-{workflow_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_id` | path | string | Yes | The Workflow id |

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

[organization_workflows_resource_envelope](../schemas/organization/organization-workflows-resource-envelope.md)

