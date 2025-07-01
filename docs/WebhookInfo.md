# WebhookInfo

Describes the current status of a webhook.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**url** | **string** | Webhook URL, may be empty if webhook is not set up | [default to undefined]
**has_custom_certificate** | **boolean** | *True*, if a custom certificate was provided for webhook certificate checks | [default to undefined]
**pending_update_count** | **number** | Number of updates awaiting delivery | [default to undefined]
**ip_address** | **string** | *Optional*. Currently used webhook IP address | [optional] [default to undefined]
**last_error_date** | **number** | *Optional*. Unix time for the most recent error that happened when trying to deliver an update via webhook | [optional] [default to undefined]
**last_error_message** | **string** | *Optional*. Error message in human-readable format for the most recent error that happened when trying to deliver an update via webhook | [optional] [default to undefined]
**last_synchronization_error_date** | **number** | *Optional*. Unix time of the most recent error that happened when trying to synchronize available updates with Telegram datacenters | [optional] [default to undefined]
**max_connections** | **number** | *Optional*. The maximum allowed number of simultaneous HTTPS connections to the webhook for update delivery | [optional] [default to undefined]
**allowed_updates** | **Array&lt;string&gt;** | *Optional*. A list of update types the bot is subscribed to. Defaults to all update types except *chat\\_member* | [optional] [default to undefined]

## Example

```typescript
import { WebhookInfo } from 'tele_rest';

const instance: WebhookInfo = {
    url,
    has_custom_certificate,
    pending_update_count,
    ip_address,
    last_error_date,
    last_error_message,
    last_synchronization_error_date,
    max_connections,
    allowed_updates,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
