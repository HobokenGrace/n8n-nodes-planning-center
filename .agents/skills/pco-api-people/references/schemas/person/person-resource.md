# person-resource

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: Person | No |  |
| `attributes` | [person_attributes](person-attributes.md) | No |  |
| `relationships` | object | No |  |
| `links` | object | No |  |

## Nested Fields

### `relationships`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `primary_campus` | object | No |  |
| `created_by` | object | No |  |

#### `relationships.primary_campus`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `links` | object | No |  |
| `data` | object | No |  |

#### `relationships.created_by`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `links` | object | No |  |
| `data` | object | No |  |

### `links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `self` | string | No |  |
| `html_url` | string | No |  |
| `addresses` | string | No |  |
| `apps` | string | No |  |
| `background_checks` | string | No |  |
| `connected_people` | string | No |  |
| `emails` | string | No |  |
| `field_data` | string | No |  |
| `household_memberships` | string | No |  |
| `households` | string | No |  |
| `inactive_reason` | string | No |  |
| `marital_status` | string | No |  |
| `message_groups` | string | No |  |
| `messages` | string | No |  |
| `name_prefix` | string | No |  |
| `name_suffix` | string | No |  |
| `notes` | string | No |  |
| `organization` | string | No |  |
| `person_apps` | string | No |  |
| `phone_numbers` | string | No |  |
| `platform_notifications` | string | No |  |
| `primary_campus` | string | No |  |
| `school` | string | No |  |
| `social_profiles` | string | No |  |
| `workflow_cards` | string | No |  |
| `workflow_shares` | string | No |  |

