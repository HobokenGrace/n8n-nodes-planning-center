# workflowcard-resource

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: WorkflowCard | No |  |
| `attributes` | [workflowcard_attributes](workflowcard-attributes.md) | No |  |
| `relationships` | object | No |  |
| `links` | object | No |  |

## Nested Fields

### `relationships`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `assignee` | object | No |  |
| `person` | object | No |  |
| `workflow` | object | No |  |
| `current_step` | object | No |  |

#### `relationships.assignee`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `links` | object | No |  |
| `data` | object | No |  |

#### `relationships.person`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `links` | object | No |  |
| `data` | object | No |  |

#### `relationships.workflow`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `links` | object | No |  |
| `data` | object | No |  |

#### `relationships.current_step`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `links` | object | No |  |
| `data` | object | No |  |

### `links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `self` | string | No |  |
| `html_url` | string | No |  |
| `activities` | string | No |  |
| `assignee` | string | No |  |
| `current_step` | string | No |  |
| `go_back` | string | No |  |
| `notes` | string | No |  |
| `person` | string | No |  |
| `promote` | string | No |  |
| `remove` | string | No |  |
| `restore` | string | No |  |
| `send_email` | string | No |  |
| `skip_step` | string | No |  |
| `snooze` | string | No |  |
| `unsnooze` | string | No |  |
| `workflow` | string | No |  |

