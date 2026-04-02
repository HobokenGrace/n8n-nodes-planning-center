# list-mailchimp-sync-status-collection-envelope

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | mailchimpsyncstatus_resource[] | No |  |
| `meta` | object | No |  |
| `links` | object | No |  |

## Nested Fields

### `meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `parent` | object | No |  |
| `total_count` | integer | No |  |
| `count` | integer | No |  |
| `prev` | object | No |  |
| `next` | object | No |  |

#### `meta.parent`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: List | No |  |

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

