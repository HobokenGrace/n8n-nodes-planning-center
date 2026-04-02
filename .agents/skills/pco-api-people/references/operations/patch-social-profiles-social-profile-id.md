# PATCH /social_profiles/{social_profile_id}

**Resource:** [SocialProfile](../resources/SocialProfile.md)
**Operation ID:** `patch--social_profiles-{social_profile_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `social_profile_id` | path | string | Yes | The SocialProfile id |

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

[organization_social_profiles_resource_envelope](../schemas/organization/organization-social-profiles-resource-envelope.md)

