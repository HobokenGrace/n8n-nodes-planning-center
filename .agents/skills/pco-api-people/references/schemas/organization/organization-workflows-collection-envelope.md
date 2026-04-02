# organization-workflows-collection-envelope

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | workflow_resource[] | No |  |
| `included` | any[] | No |  |
| `meta` | object | No |  |
| `links` | object | No |  |

## Nested Fields

### `meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_include` | enum: category,shares,steps | No |  |
| `parent` | object | No |  |
| `total_count` | integer | No |  |
| `count` | integer | No |  |
| `prev` | object | No |  |
| `next` | object | No |  |
| `can_order_by` | enum: name,created_at,updated_at,deleted_at,archived_at,campus_id,workflow_category_id | No |  |
| `can_query_by` | enum: name,created_at,updated_at,deleted_at,archived_at,campus_id,workflow_category_id,ready,id | No |  |
| `can_filter` | enum: not_archived,archived,only_deleted,with_deleted,with_recoverable,with_steps,recently_viewed,unassigned,has_my_cards,manage_cards_allowed | No |  |

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

