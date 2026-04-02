# message-message-group-collection-envelope

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | messagegroup_resource[] | No |  |
| `included` | any[] | No |  |
| `meta` | object | No |  |
| `links` | object | No |  |

## Nested Fields

### `meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_include` | enum: app,from,messages | No |  |
| `parent` | object | No |  |
| `total_count` | integer | No |  |
| `count` | integer | No |  |
| `prev` | object | No |  |
| `next` | object | No |  |
| `can_order_by` | enum: uuid,message_type,from_address,subject,message_count,system_message,transactional_message,contains_user_generated_content,created_at,reply_to_name,reply_to_address | No |  |
| `can_query_by` | enum: uuid,message_type,from_address,subject,message_count,system_message,transactional_message,contains_user_generated_content,created_at,reply_to_name,reply_to_address,app_name | No |  |

#### `meta.parent`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: Message | No |  |

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

