# GET /social_profiles/{social_profile_id}

**Resource:** [SocialProfile](../resources/SocialProfile.md)
**Operation ID:** `get--social_profiles-{social_profile_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `social_profile_id` | path | string | Yes | The SocialProfile id |

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

[organization_social_profiles_resource_envelope](../schemas/organization/organization-social-profiles-resource-envelope.md)

