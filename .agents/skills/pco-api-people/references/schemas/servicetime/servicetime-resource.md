# servicetime-resource

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: ServiceTime | No |  |
| `attributes` | [servicetime_attributes](servicetime-attributes.md) | No |  |
| `relationships` | object | No |  |
| `links` | object | No |  |

## Nested Fields

### `relationships`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `organization` | object | No |  |
| `campus` | object | No |  |

#### `relationships.organization`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `links` | object | No |  |
| `data` | object | No |  |

#### `relationships.campus`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `links` | object | No |  |
| `data` | object | No |  |

### `links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `self` | string | No |  |

