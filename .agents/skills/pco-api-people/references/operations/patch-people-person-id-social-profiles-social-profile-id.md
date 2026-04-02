# PATCH /people/{person_id}/social_profiles/{social_profile_id}

**Resource:** [Person](../resources/Person.md)
**Operation ID:** `patch--people-{person_id}-social_profiles-{social_profile_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `person_id` | path | string | Yes | The Person id |
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

[person_social_profiles_resource_envelope](../schemas/person/person-social-profiles-resource-envelope.md)

