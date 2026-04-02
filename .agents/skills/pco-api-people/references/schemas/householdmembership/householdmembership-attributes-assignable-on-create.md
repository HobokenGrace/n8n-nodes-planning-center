# householdmembership-attributes-assignable-on-create

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `person_id` | string | No |  |
| `pending` | boolean | No | False when a person's membership in a household is unverified. |
| `household_role` | string | No | The role of the person within the household. Possible values are: `adult`, `child_or_dependent`, `other_adult`or`parent_guardian`. |

