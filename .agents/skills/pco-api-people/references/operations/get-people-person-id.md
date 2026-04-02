# GET /people/{person_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |

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

[organization_people_resource_envelope](../schemas/organization/organization-people-resource-envelope.md)

