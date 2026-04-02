# PATCH /membership_types/{membership_type_id}

**Resource:** [MembershipType](../resources/MembershipType.md)
**Operation ID:** `patch--membership_types-{membership_type_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `membership_type_id` | path | string | Yes | The MembershipType id |

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

[organization_membership_types_resource_envelope](../schemas/organization/organization-membership-types-resource-envelope.md)

