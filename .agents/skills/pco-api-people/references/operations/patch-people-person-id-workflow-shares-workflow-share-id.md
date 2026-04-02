# PATCH /people/{person_id}/workflow_shares/{workflow_share_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `patch--people-{person_id}-workflow_shares-{workflow_share_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `workflow_share_id` | path | string | Yes | The WorkflowShare id |

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

[person_workflow_shares_resource_envelope](../schemas/person/person-workflow-shares-resource-envelope.md)

