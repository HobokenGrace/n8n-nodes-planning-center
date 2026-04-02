# formfield-relationships-assignable-on-update

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fieldable` | object | No | Polymorphic. Fieldable can be any of the following: FieldDefinition, NoteCategory, or Workflow.  |

## Nested Fields

### `fieldable`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | object | No |  |

#### `fieldable.data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | No |  |
| `id` | string | No |  |

