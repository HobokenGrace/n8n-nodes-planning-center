# GET /forms/{form_id}/form_submissions/{form_submission_id}/person/{person_id}

**Resource:** [Form](../resources/Form.md)
**Operation ID:** `get--forms-{form_id}-form_submissions-{form_submission_id}-person-{person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `form_id` | path | string | Yes | The Form id |
| `form_submission_id` | path | string | Yes | The FormSubmission id |
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

[form_submission_person_resource_envelope](../schemas/form/form-submission-person-resource-envelope.md)

