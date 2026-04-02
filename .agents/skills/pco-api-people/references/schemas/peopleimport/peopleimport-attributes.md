# peopleimport-attributes

A PeopleImport is a record of an ongoing or previous import from a CSV file.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `attribs` | string | No |  |
| `created_at` | string (date-time) | No |  |
| `processed_at` | string (date-time) | No |  |
| `status` | string | No | Possible values: `matching`, `processing_preview`, `previewing`, `processing_import`, `complete`, `undone`, or `undoing` |
| `undone_at` | string (date-time) | No |  |
| `updated_at` | string (date-time) | No |  |

