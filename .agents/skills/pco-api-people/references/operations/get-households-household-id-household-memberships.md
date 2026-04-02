# GET /households/{household_id}/household_memberships

**Resource:** [Household](../resources/Household.md)
**Operation ID:** `get--households-{household_id}-household_memberships`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `household_id` | path | string | Yes | The Household id |

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

[household_household_memberships_collection_envelope](../schemas/household/household-household-memberships-collection-envelope.md)

