# workflow-resource

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: Workflow | No |  |
| `attributes` | [workflow_attributes](workflow-attributes.md) | No |  |
| `relationships` | object | No |  |
| `links` | object | No |  |

## Nested Fields

### `relationships`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `workflow_category` | object | No |  |
| `campus` | object | No |  |

#### `relationships.workflow_category`

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
| `html_url` | string | No |  |
| `cards` | string | No |  |
| `category` | string | No |  |
| `shared_people` | string | No |  |
| `shares` | string | No |  |
| `steps` | string | No |  |

