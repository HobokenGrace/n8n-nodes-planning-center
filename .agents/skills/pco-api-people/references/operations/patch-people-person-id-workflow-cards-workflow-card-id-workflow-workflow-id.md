# PATCH /people/{person_id}/workflow_cards/{workflow_card_id}/workflow/{workflow_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `patch--people-{person_id}-workflow_cards-{workflow_card_id}-workflow-{workflow_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `workflow_card_id` | path | string | Yes | The WorkflowCard id |
| `workflow_id` | path | string | Yes | The Workflow id |

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

[workflow_card_workflow_resource_envelope](../schemas/workflow/workflow-card-workflow-resource-envelope.md)

