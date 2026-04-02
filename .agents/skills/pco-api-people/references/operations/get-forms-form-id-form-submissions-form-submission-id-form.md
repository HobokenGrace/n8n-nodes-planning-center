# GET /forms/{form_id}/form_submissions/{form_submission_id}/form

**Resource:** [Form](../resources/Form.md)
**Operation ID:** `get--forms-{form_id}-form_submissions-{form_submission_id}-form`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `form_id` | path | string | Yes | The Form id |
| `form_submission_id` | path | string | Yes | The FormSubmission id |

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

[form_submission_form_collection_envelope](../schemas/form/form-submission-form-collection-envelope.md)

