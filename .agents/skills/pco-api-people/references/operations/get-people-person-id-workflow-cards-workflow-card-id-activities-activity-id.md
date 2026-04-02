# GET /people/{person_id}/workflow_cards/{workflow_card_id}/activities/{activity_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}-workflow_cards-{workflow_card_id}-activities-{activity_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `workflow_card_id` | path | string | Yes | The WorkflowCard id |
| `activity_id` | path | string | Yes | The Activity id |

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

[workflow_card_activities_resource_envelope](../schemas/workflow/workflow-card-activities-resource-envelope.md)

