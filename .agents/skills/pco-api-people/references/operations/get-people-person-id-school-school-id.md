# GET /people/{person_id}/school/{school_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}-school-{school_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `school_id` | path | string | Yes | The School id |

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

[person_school_resource_envelope](../schemas/person/person-school-resource-envelope.md)

