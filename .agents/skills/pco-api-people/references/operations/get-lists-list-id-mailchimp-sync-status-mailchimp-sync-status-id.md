# GET /lists/{list_id}/mailchimp_sync_status/{mailchimp_sync_status_id}

**Resource:** [List](../resources/List.md)
**Operation ID:** `get--lists-{list_id}-mailchimp_sync_status-{mailchimp_sync_status_id}`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `list_id` | path | string | Yes | The List id |
| `mailchimp_sync_status_id` | path | string | Yes | The MailchimpSyncStatus id |

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

[list_mailchimp_sync_status_resource_envelope](../schemas/list/list-mailchimp-sync-status-resource-envelope.md)

