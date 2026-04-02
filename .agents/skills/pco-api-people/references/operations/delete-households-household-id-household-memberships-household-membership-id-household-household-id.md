# DELETE /households/{household_id}/household_memberships/{household_membership_id}/household/{household_id}

**Resource:** [Household](../resources/Household.md)
**Operation ID:** `delete--households-{household_id}-household_memberships-{household_membership_id}-household-{household_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `household_id` | path | string | Yes | The Household id |
| `household_membership_id` | path | string | Yes | The HouseholdMembership id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

