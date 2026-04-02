# PATCH /households/{household_id}/people/{person_id}

**Resource:** [Household](../resources/Household.md)
**Operation ID:** `patch--households-{household_id}-people-{person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `household_id` | path | string | Yes | The Household id |
| `person_id` | path | string | Yes | The Person id |

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

[household_people_resource_envelope](../schemas/household/household-people-resource-envelope.md)

