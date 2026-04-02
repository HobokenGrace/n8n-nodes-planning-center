# GET /social_profiles/{social_profile_id}/person

**Resource:** [SocialProfile](../resources/SocialProfile.md)
**Operation ID:** `get--social_profiles-{social_profile_id}-person`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `social_profile_id` | path | string | Yes | The SocialProfile id |

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

[social_profile_person_collection_envelope](../schemas/social/social-profile-person-collection-envelope.md)

