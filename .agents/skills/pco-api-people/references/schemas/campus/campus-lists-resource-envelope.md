# campus-lists-resource-envelope

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | [list_resource](list-resource.md) | No |  |
| `included` | any[] | No |  |
| `meta` | object | No |  |

## Nested Fields

### `meta`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `can_include` | enum: campus,category,created_by,mailchimp_sync_status,people,rules,shares,updated_by | No |  |
| `parent` | object | No |  |

#### `meta.parent`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: Campus | No |  |

