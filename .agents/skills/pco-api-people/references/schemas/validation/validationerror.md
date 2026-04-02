# validationerror

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `errors` | object[] | No |  |

## Nested Fields

### `errors`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | enum: 422 | No |  |
| `detail` | string | No |  |
| `title` | enum: Validation Error | No |  |
| `meta` | object | No |  |
| `source` | object | No |  |

#### `errors.meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `resource` | string | No |  |
| `associated_resources` | object[] | No |  |

#### `errors.source`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `parameter` | string | No |  |

