# POST /households/{household_id}/household_memberships

**Resource:** [Household](../resources/Household.md)
**Operation ID:** `post--households-{household_id}-household_memberships`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `household_id` | path | string | Yes | The Household id |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successful create response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[household_household_memberships_resource_envelope](../schemas/household/household-household-memberships-resource-envelope.md)

