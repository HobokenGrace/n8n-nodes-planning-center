# PATCH /background_checks/{background_check_id}/person/{person_id}

**Resource:** [BackgroundCheck](../resources/BackgroundCheck.md)
**Operation ID:** `patch--background_checks-{background_check_id}-person-{person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `background_check_id` | path | string | Yes | The BackgroundCheck id |
| `person_id` | path | string | Yes | The Person id |

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

[background_check_person_resource_envelope](../schemas/background/background-check-person-resource-envelope.md)

