# householdmembership-attributes

A household membership is the linking record between a household and a person.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `household_role` | string | No | The role of the person within the household. Possible values are: `adult`, `child_or_dependent`, `other_adult`or`parent_guardian`. |
| `pending` | boolean | No | False when a person's membership in a household is unverified. |
| `person_name` | string | No |  |

