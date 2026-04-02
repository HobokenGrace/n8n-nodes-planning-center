# form-field-options-collection-envelope

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | formfieldoption_resource[] | No |  |
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
| `can_order_by` | enum: sequence,created_at,updated_at | No |  |

#### `meta.parent`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: FormField | No |  |

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

