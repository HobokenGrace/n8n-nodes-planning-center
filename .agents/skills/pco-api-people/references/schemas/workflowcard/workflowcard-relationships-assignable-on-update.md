# workflowcard-relationships-assignable-on-update

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `assignee` | object | No |  |
| `person` | object | No |  |

## Nested Fields

### `assignee`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |

#### `assignee.data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: Assignee | No |  |
| `id` | string | No |  |

### `person`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |

#### `person.data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: Person | No |  |
| `id` | string | No |  |

