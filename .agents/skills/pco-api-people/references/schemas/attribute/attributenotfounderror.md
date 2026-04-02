# attributenotfounderror

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
| `code` | enum: attribute_resource_not_found | No |  |
| `detail` | string | No |  |
| `title` | enum: Attribute Resource Not Found | No |  |
| `source` | object | No |  |

#### `errors.source`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `parameter` | string | No |  |

