# GET /note_category_subscriptions/{note_category_subscription_id}/person

**Resource:** [NoteCategorySubscription](../resources/NoteCategorySubscription.md)
**Operation ID:** `get--note_category_subscriptions-{note_category_subscription_id}-person`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `note_category_subscription_id` | path | string | Yes | The NoteCategorySubscription id |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful collection response |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[note_category_subscription_person_collection_envelope](../schemas/note/note-category-subscription-person-collection-envelope.md)

