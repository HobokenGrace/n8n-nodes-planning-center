# PATCH /households/{household_id}/household_memberships/{household_membership_id}

**Resource:** [Household](../resources/Household.md)
**Operation ID:** `patch--households-{household_id}-household_memberships-{household_membership_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `household_id` | path | string | Yes | The Household id |
| `household_membership_id` | path | string | Yes | The HouseholdMembership id |

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

[household_household_memberships_resource_envelope](../schemas/household/household-household-memberships-resource-envelope.md)

