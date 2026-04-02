# GET /note_category_subscriptions/{note_category_subscription_id}/person/{person_id}

**Resource:** [NoteCategorySubscription](../resources/NoteCategorySubscription.md)
**Operation ID:** `get--note_category_subscriptions-{note_category_subscription_id}-person-{person_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_category_subscription_id` | path | string | Yes | The NoteCategorySubscription id |
| `person_id` | path | string | Yes | The Person id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful read response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[note_category_subscription_person_resource_envelope](../schemas/note/note-category-subscription-person-resource-envelope.md)

