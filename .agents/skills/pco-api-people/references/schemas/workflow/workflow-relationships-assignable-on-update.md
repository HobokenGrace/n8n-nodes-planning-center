# workflow-relationships-assignable-on-update

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `workflow_category` | object | No |  |
| `campus` | object | No |  |

## Nested Fields

### `workflow_category`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |

#### `workflow_category.data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: WorkflowCategory | No |  |
| `id` | string | No |  |

### `campus`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |

#### `campus.data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: Campus | No |  |
| `id` | string | No |  |

