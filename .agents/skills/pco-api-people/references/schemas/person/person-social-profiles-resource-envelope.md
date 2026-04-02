# person-social-profiles-resource-envelope

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | [socialprofile_resource](socialprofile-resource.md) | No |  |
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
| `type` | enum: Person | No |  |

