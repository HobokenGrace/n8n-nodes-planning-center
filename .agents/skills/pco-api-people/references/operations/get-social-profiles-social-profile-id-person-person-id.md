# GET /social_profiles/{social_profile_id}/person/{person_id}

**Resource:** [SocialProfile](../resources/SocialProfile.md)
**Operation ID:** `get--social_profiles-{social_profile_id}-person-{person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `social_profile_id` | path | string | Yes | The SocialProfile id |
| `person_id` | path | string | Yes | The Person id |

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

[social_profile_person_resource_envelope](../schemas/social/social-profile-person-resource-envelope.md)

