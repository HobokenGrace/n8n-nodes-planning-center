# backgroundcheck-attributes-assignable-on-create

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `note` | string | No |  |
| `status` | string | No | Possible values: `awaiting_applicant`, `expired_invitation`, `report_processing`, `needs_review`, `complete_clear`, `complete_not_clear`, `canceled` |
| `report_url` | string | No | This URL should require authentication |
| `expires_on` | string (date) | No | Leave blank to use organization's expiration policy |
| `completed_at` | string (date-time) | No | Returns `null` until background check reaches a completed status. When creating completed background checks, leave blank to use current date and time. |

