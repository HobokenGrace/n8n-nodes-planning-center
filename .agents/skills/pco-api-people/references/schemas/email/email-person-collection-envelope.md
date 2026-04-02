# email-person-collection-envelope

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | person_resource[] | No |  |
| `included` | any[] | No |  |
| `meta` | object | No |  |
| `links` | object | No |  |

## Nested Fields

### `meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_include` | enum: addresses,emails,field_data,households,inactive_reason,marital_status,name_prefix,name_suffix,organization,person_apps,phone_numbers,platform_notifications,primary_campus,school,social_profiles | No |  |
| `parent` | object | No |  |
| `total_count` | integer | No |  |
| `count` | integer | No |  |
| `prev` | object | No |  |
| `next` | object | No |  |
| `can_order_by` | enum: accounting_administrator,anniversary,birthdate,child,given_name,grade,graduation_year,middle_name,nickname,people_permissions,site_administrator,gender,inactivated_at,created_at,updated_at,first_name,last_name,remote_id,membership,status | No |  |
| `can_query_by` | enum: accounting_administrator,anniversary,birthdate,child,given_name,grade,graduation_year,middle_name,nickname,people_permissions,site_administrator,gender,inactivated_at,medical_notes,membership,created_at,updated_at,search_name,search_name_or_email,search_name_or_email_or_phone_number,search_phone_number,search_phone_number_e164,mfa_configured,first_name,last_name,id,primary_campus_id,remote_id,status | No |  |

#### `meta.parent`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: Email | No |  |

#### `meta.prev`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `offset` | integer | No |  |

#### `meta.next`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `offset` | integer | No |  |

### `links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `self` | string | No |  |
| `prev` | string | No |  |
| `next` | string | No |  |

