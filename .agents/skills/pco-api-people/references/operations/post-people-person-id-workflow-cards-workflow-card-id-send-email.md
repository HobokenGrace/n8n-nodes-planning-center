# POST /people/{person_id}/workflow_cards/{workflow_card_id}/send_email

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `post--people-{person_id}-workflow_cards-{workflow_card_id}-send_email`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `workflow_card_id` | path | string | Yes | The WorkflowCard id |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successful action response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |
| 500 | (reference) |

