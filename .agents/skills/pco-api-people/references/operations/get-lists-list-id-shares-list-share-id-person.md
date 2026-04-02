# GET /lists/{list_id}/shares/{list_share_id}/person

**Resource:** [List](../resources/List.md)
**Operation ID:** `get--lists-{list_id}-shares-{list_share_id}-person`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | string | Yes | The List id |
| `list_share_id` | path | string | Yes | The ListShare id |

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

[list_share_person_collection_envelope](../schemas/list/list-share-person-collection-envelope.md)

