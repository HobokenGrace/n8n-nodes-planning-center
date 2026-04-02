# GET /forms/{form_id}/form_submissions/{form_submission_id}

**Resource:** [Form](../resources/Form.md)
**Operation ID:** `get--forms-{form_id}-form_submissions-{form_submission_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `form_id` | path | string | Yes | The Form id |
| `form_submission_id` | path | string | Yes | The FormSubmission id |

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

[form_form_submissions_resource_envelope](../schemas/form/form-form-submissions-resource-envelope.md)

