# list-shares-resource-envelope

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | [listshare_resource](listshare-resource.md) | No |  |
| `included` | any[] | No |  |
| `meta` | object | No |  |

## Nested Fields

### `meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_include` | enum: person | No |  |
| `parent` | object | No |  |

#### `meta.parent`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: List | No |  |

