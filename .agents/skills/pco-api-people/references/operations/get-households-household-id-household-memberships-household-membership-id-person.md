# GET /households/{household_id}/household_memberships/{household_membership_id}/person

**Resource:** [Household](../resources/Household.md)
**Operation ID:** `get--households-{household_id}-household_memberships-{household_membership_id}-person`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `household_id` | path | string | Yes | The Household id |
| `household_membership_id` | path | string | Yes | The HouseholdMembership id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful collection response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[household_membership_person_collection_envelope](../schemas/household/household-membership-person-collection-envelope.md)

