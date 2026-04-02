# GET /background_checks/{background_check_id}/person

**Resource:** [BackgroundCheck](../resources/BackgroundCheck.md)
**Operation ID:** `get--background_checks-{background_check_id}-person`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `background_check_id` | path | string | Yes | The BackgroundCheck id |

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

[background_check_person_collection_envelope](../schemas/background/background-check-person-collection-envelope.md)

