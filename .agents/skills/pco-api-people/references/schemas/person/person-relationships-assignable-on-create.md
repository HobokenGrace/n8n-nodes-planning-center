# person-relationships-assignable-on-create

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `primary_campus` | object | No |  |
| `created_by` | object | No |  |

## Nested Fields

### `primary_campus`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |

#### `primary_campus.data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: PrimaryCampus | No |  |
| `id` | string | No |  |

### `created_by`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |

#### `created_by.data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: Person | No |  |
| `id` | string | No |  |

