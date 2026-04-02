# notuniqueerror

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `errors` | object[] | No |  |

## Nested Fields

### `errors`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | enum: 409 | No |  |
| `detail` | enum: The record you are trying to create/update already exists | No |  |
| `title` | enum: Duplicate Record | No |  |

