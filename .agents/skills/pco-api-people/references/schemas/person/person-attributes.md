# person-attributes

A person record represents a single member/user of the application. Each person has different permissions that determine how the user can use this app (if at all).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accounting_administrator` | boolean | No |  |
| `anniversary` | string (date) | No |  |
| `avatar` | string | No | File UUID (see [File Uploads](#file-uploads) section) |
| `birthdate` | string (date) | No |  |
| `can_create_forms` | boolean | No |  |
| `can_email_lists` | boolean | No |  |
| `child` | boolean | No |  |
| `created_at` | string (date-time) | No |  |
| `demographic_avatar_url` | string | No |  |
| `directory_shared_info` | object | No | Only available when requested with the `?fields` param |
| `directory_status` | string | No |  |
| `first_name` | string | No |  |
| `gender` | string | No |  |
| `given_name` | string | No |  |
| `grade` | integer | No |  |
| `graduation_year` | integer | No |  |
| `inactivated_at` | string (date-time) | No | Set to an ISO 8601 date or time to make the profile inactive. Set to "null" to reactivate the profile. |
| `last_name` | string | No |  |
| `login_identifier` | string | No |  |
| `medical_notes` | string | No |  |
| `membership` | string | No |  |
| `mfa_configured` | boolean | No | Only available when requested with the `?fields` param |
| `middle_name` | string | No |  |
| `name` | string | No |  |
| `nickname` | string | No |  |
| `passed_background_check` | boolean | No |  |
| `people_permissions` | string | No |  |
| `primary_email_address` | string | No | Only available when requested with the `?fields` param |
| `remote_id` | integer | No |  |
| `resource_permission_flags` | object | No |  |
| `school_type` | string | No |  |
| `search_name` | string | No |  |
| `search_name_or_email` | string | No |  |
| `search_name_or_email_or_phone_number` | string | No |  |
| `search_phone_number` | string | No |  |
| `search_phone_number_e164` | string | No |  |
| `site_administrator` | boolean | No |  |
| `status` | string | No | Set to "inactive" to set "inactivated_at" to the current time and make the profile inactive. Set to anything else to clear "inactivated_at" and reactivate the profile. |
| `stripe_customer_identifier` | string | No | Only available when requested with the `?fields` param |
| `updated_at` | string (date-time) | No |  |

