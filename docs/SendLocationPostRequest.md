# SendLocationPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessagePostRequestChatId**](SendMessagePostRequestChatId.md) |  | [default to undefined]
**latitude** | **number** | Latitude of the location | [default to undefined]
**longitude** | **number** | Longitude of the location | [default to undefined]
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which the message will be sent | [optional] [default to undefined]
**message_thread_id** | **number** | Unique identifier for the target message thread (topic) of the forum; for forum supergroups only | [optional] [default to undefined]
**horizontal_accuracy** | **number** | The radius of uncertainty for the location, measured in meters; 0-1500 | [optional] [default to undefined]
**live_period** | **number** | Period in seconds during which the location will be updated (see [Live Locations](https://telegram.org/blog/live-locations), should be between 60 and 86400, or 0x7FFFFFFF for live locations that can be edited indefinitely. | [optional] [default to undefined]
**heading** | **number** | For live locations, a direction in which the user is moving, in degrees. Must be between 1 and 360 if specified. | [optional] [default to undefined]
**proximity_alert_radius** | **number** | For live locations, a maximum distance for proximity alerts about approaching another chat member, in meters. Must be between 1 and 100000 if specified. | [optional] [default to undefined]
**disable_notification** | **boolean** | Sends the message [silently](https://telegram.org/blog/channels-2-0#silent-messages). Users will receive a notification with no sound. | [optional] [default to undefined]
**protect_content** | **boolean** | Protects the contents of the sent message from forwarding and saving | [optional] [default to undefined]
**allow_paid_broadcast** | **boolean** | Pass *True* to allow up to 1000 messages per second, ignoring [broadcasting limits](https://core.telegram.org/bots/faq#how-can-i-message-all-of-my-bot-39s-subscribers-at-once) for a fee of 0.1 Telegram Stars per message. The relevant Stars will be withdrawn from the bot\&#39;s balance | [optional] [default to undefined]
**message_effect_id** | **string** | Unique identifier of the message effect to be added to the message; for private chats only | [optional] [default to undefined]
**reply_parameters** | [**ReplyParameters**](ReplyParameters.md) |  | [optional] [default to undefined]
**reply_markup** | [**SendMessagePostRequestReplyMarkup**](SendMessagePostRequestReplyMarkup.md) |  | [optional] [default to undefined]

## Example

```typescript
import { SendLocationPostRequest } from 'tele_rest';

const instance: SendLocationPostRequest = {
    chat_id,
    latitude,
    longitude,
    business_connection_id,
    message_thread_id,
    horizontal_accuracy,
    live_period,
    heading,
    proximity_alert_radius,
    disable_notification,
    protect_content,
    allow_paid_broadcast,
    message_effect_id,
    reply_parameters,
    reply_markup,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
