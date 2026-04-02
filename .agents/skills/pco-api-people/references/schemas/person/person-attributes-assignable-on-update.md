# person-attributes-assignable-on-update

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accounting_administrator` | boolean | No |  |
| `anniversary` | string (date) | No |  |
| `birthdate` | string (date) | No |  |
| `child` | boolean | No |  |
| `given_name` | string | No |  |
| `grade` | integer | No |  |
| `graduation_year` | integer | No |  |
| `middle_name` | string | No |  |
| `nickname` | string | No |  |
| `people_permissions` | string | No |  |
| `site_administrator` | boolean | No |  |
| `gender` | string | No |  |
| `inactivated_at` | string (date-time) | No | Set to an ISO 8601 date or time to make the profile inactive. Set to "null" to reactivate the profile. |
| `medical_notes` | string | No |  |
| `membership` | string | No |  |
| `stripe_customer_identifier` | string | No | Only available when requested with the `?fields` param |
| `avatar` | string | No | File UUID (see [File Uploads](#file-uploads) section) |
| `first_name` | string | No |  |
| `last_name` | string | No |  |
| `gender_id` | string | No |  |
| `inactive_reason_id` | string | No |  |
| `marital_status_id` | string | No |  |
| `membership_status_id` | string | No |  |
| `name_prefix_id` | string | No |  |
| `name_prefix` | string | No |  |
| `name_suffix_id` | string | No |  |
| `name_suffix` | string | No |  |
| `primary_campus_id` | string | No |  |
| `remote_id` | integer | No |  |
| `school_id` | string | No |  |
| `status` | string | No | Set to "inactive" to set "inactivated_at" to the current time and make the profile inactive. Set to anything else to clear "inactivated_at" and reactivate the profile. |

