# GET /people/{person_id}/organization/{organization_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `get--people-{person_id}-organization-{organization_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
| `organization_id` | path | string | Yes | The Organization id |

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

[person_organization_resource_envelope](../schemas/person/person-organization-resource-envelope.md)

