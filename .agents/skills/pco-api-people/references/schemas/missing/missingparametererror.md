# missingparametererror

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `errors` | object[] | No |  |

## Nested Fields

### `errors`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | enum: 400 | No |  |
| `code` | enum: missing_parameter | No |  |
| `detail` | string | No |  |
| `title` | enum: A required parameter wasn't supplied | No |  |
| `meta` | object | No |  |

#### `errors.meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `param` | string | No |  |

