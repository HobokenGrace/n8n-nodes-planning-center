# fielddatum-resource

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `type` | enum: FieldDatum | No |  |
| `attributes` | [fielddatum_attributes](fielddatum-attributes.md) | No |  |
| `relationships` | object | No |  |
| `links` | object | No |  |

## Nested Fields

### `relationships`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `field_definition` | object | No |  |
| `customizable` | object | No | Currently, the only customizable relationship is with `Person`. |

#### `relationships.field_definition`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `links` | object | No |  |
| `data` | object | No |  |

#### `relationships.customizable`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `links` | object | No |  |
| `data` | object | No |  |

### `links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `self` | string | No |  |
| `field_definition` | string | No |  |
| `field_option` | string | No |  |
| `person` | string | No |  |
| `tab` | string | No |  |

