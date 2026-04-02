# PATCH /people/{person_id}/marital_status/{marital_status_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `patch--people-{person_id}-marital_status-{marital_status_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `marital_status_id` | path | string | Yes | The MaritalStatus id |

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

[person_marital_status_resource_envelope](../schemas/person/person-marital-status-resource-envelope.md)

