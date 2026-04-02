# GET /people/{person_id}/workflow_shares/{workflow_share_id}/person/{person_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}-workflow_shares-{workflow_share_id}-person-{person_id}`

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

[workflow_share_person_resource_envelope](../schemas/workflow/workflow-share-person-resource-envelope.md)

