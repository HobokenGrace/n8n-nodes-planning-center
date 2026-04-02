# organization-messages-collection-envelope

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | message_resource[] | No |  |
| `included` | any[] | No |  |
| `meta` | object | No |  |
| `links` | object | No |  |

## Nested Fields

### `meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_include` | enum: message_group,to | No |  |
| `parent` | object | No |  |
| `total_count` | integer | No |  |
| `count` | integer | No |  |
| `prev` | object | No |  |
| `next` | object | No |  |
| `can_order_by` | enum: kind,to_addresses,subject,delivery_status,reject_reason,created_at,sent_at,bounced_at,rejection_notification_sent_at,file,from_name,from_address,app_name | No |  |
| `can_query_by` | enum: kind,to_addresses,subject,delivery_status,reject_reason,created_at,sent_at,bounced_at,rejection_notification_sent_at,from_address,app_name,file | No |  |
| `can_filter` | enum: created_after | No |  |

#### `meta.parent`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: Organization | No |  |

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

