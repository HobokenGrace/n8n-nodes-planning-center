# GET /people/{person_id}/workflow_shares/{workflow_share_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}-workflow_shares-{workflow_share_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `workflow_share_id` | path | string | Yes | The WorkflowShare id |

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

[person_workflow_shares_resource_envelope](../schemas/person/person-workflow-shares-resource-envelope.md)

