# notecategorysubscription-relationships-assignable-on-create

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `person` | object | No |  |
| `note_category` | object | No |  |

## Nested Fields

### `person`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |

#### `person.data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: Person | No |  |
| `id` | string | No |  |

### `note_category`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |

#### `note_category.data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: NoteCategory | No |  |
| `id` | string | No |  |

