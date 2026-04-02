# PATCH /forms/{form_id}/campus/{campus_id}

**Resource:** [Form](../resources/Form.md)
**Operation ID:** `patch--forms-{form_id}-campus-{campus_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `form_id` | path | string | Yes | The Form id |
| `campus_id` | path | string | Yes | The Campus id |

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

[form_campus_resource_envelope](../schemas/form/form-campus-resource-envelope.md)

