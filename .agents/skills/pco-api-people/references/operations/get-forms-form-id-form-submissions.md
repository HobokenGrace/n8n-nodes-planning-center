# GET /forms/{form_id}/form_submissions

**Resource:** [Form](../resources/Form.md)
**Operation ID:** `get--forms-{form_id}-form_submissions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `form_id` | path | string | Yes | The Form id |

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

[form_form_submissions_collection_envelope](../schemas/form/form-form-submissions-collection-envelope.md)

