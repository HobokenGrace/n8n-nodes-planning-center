# DELETE /social_profiles/{social_profile_id}/person/{person_id}

**Resource:** [SocialProfile](../resources/SocialProfile.md)
**Operation ID:** `delete--social_profiles-{social_profile_id}-person-{person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `social_profile_id` | path | string | Yes | The SocialProfile id |
| `person_id` | path | string | Yes | The Person id |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Successful destroy response (no content) |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

