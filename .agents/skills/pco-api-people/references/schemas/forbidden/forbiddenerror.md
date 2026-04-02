# forbiddenerror

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `errors` | object[] | No |  |

## Nested Fields

### `errors`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | enum: 403 | No |  |
| `detail` | enum: You do not have access to this resource | No |  |
| `title` | enum: Forbidden | No |  |
| `meta` | object | No |  |

#### `errors.meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No |  |

