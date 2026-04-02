# message-attributes

A message is an individual email or sms text sent to a member. Every message has a parent message group.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `app_name` | string | No |  |
| `bounced_at` | string (date-time) | No |  |
| `created_at` | string (date-time) | No |  |
| `delivery_status` | string | No |  |
| `file` | string | No |  |
| `from_address` | string | No |  |
| `from_name` | string | No |  |
| `kind` | string | No | Possible values: `email`, `sms`, or `church_center_message` |
| `message_type` | string | No |  |
| `read_at` | string (date-time) | No |  |
| `reject_reason` | string | No |  |
| `rejection_notification_sent_at` | string (date-time) | No |  |
| `sent_at` | string (date-time) | No |  |
| `subject` | string | No |  |
| `to_addresses` | string | No |  |

