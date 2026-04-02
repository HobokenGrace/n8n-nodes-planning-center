# form-relationships-assignable-on-create

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `campus` | object | No |  |
| `form_category` | object | No |  |

## Nested Fields

### `campus`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |

#### `campus.data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: Campus | No |  |
| `id` | string | No |  |

### `form_category`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |

#### `form_category.data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: FormCategory | No |  |
| `id` | string | No |  |

