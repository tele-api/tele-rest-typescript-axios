# SendMediaGroupRequest

Request parameters for sendMediaGroup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessageRequestChatId**](SendMessageRequestChatId.md) |  | [default to undefined]
**media** | [**Array&lt;SendMediaGroupRequestMediaInner&gt;**](SendMediaGroupRequestMediaInner.md) | A JSON-serialized array describing messages to be sent, must include 2-10 items | [default to undefined]
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which the message will be sent | [optional] [default to undefined]
**message_thread_id** | **number** | Unique identifier for the target message thread (topic) of the forum; for forum supergroups only | [optional] [default to undefined]
**disable_notification** | **boolean** | Sends messages [silently](https://telegram.org/blog/channels-2-0#silent-messages). Users will receive a notification with no sound. | [optional] [default to undefined]
**protect_content** | **boolean** | Protects the contents of the sent messages from forwarding and saving | [optional] [default to undefined]
**allow_paid_broadcast** | **boolean** | Pass *True* to allow up to 1000 messages per second, ignoring [broadcasting limits](https://core.telegram.org/bots/faq#how-can-i-message-all-of-my-bot-39s-subscribers-at-once) for a fee of 0.1 Telegram Stars per message. The relevant Stars will be withdrawn from the bot\&#39;s balance | [optional] [default to undefined]
**message_effect_id** | **string** | Unique identifier of the message effect to be added to the message; for private chats only | [optional] [default to undefined]
**reply_parameters** | [**ReplyParameters**](ReplyParameters.md) |  | [optional] [default to undefined]

## Example

```typescript
import { SendMediaGroupRequest } from 'tele_rest';

const instance: SendMediaGroupRequest = {
    chat_id,
    media,
    business_connection_id,
    message_thread_id,
    disable_notification,
    protect_content,
    allow_paid_broadcast,
    message_effect_id,
    reply_parameters,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
