# SendStickerRequest

Request parameters for sendSticker

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessageRequestChatId**](SendMessageRequestChatId.md) |  | [default to undefined]
**sticker** | **string** |  | [default to undefined]
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which the message will be sent | [optional] [default to undefined]
**message_thread_id** | **number** | Unique identifier for the target message thread (topic) of the forum; for forum supergroups only | [optional] [default to undefined]
**emoji** | **string** | Emoji associated with the sticker; only for just uploaded stickers | [optional] [default to undefined]
**disable_notification** | **boolean** | Sends the message [silently](https://telegram.org/blog/channels-2-0#silent-messages). Users will receive a notification with no sound. | [optional] [default to undefined]
**protect_content** | **boolean** | Protects the contents of the sent message from forwarding and saving | [optional] [default to undefined]
**allow_paid_broadcast** | **boolean** | Pass *True* to allow up to 1000 messages per second, ignoring [broadcasting limits](https://core.telegram.org/bots/faq#how-can-i-message-all-of-my-bot-39s-subscribers-at-once) for a fee of 0.1 Telegram Stars per message. The relevant Stars will be withdrawn from the bot\&#39;s balance | [optional] [default to undefined]
**message_effect_id** | **string** | Unique identifier of the message effect to be added to the message; for private chats only | [optional] [default to undefined]
**reply_parameters** | [**ReplyParameters**](ReplyParameters.md) |  | [optional] [default to undefined]
**reply_markup** | [**SendMessageRequestReplyMarkup**](SendMessageRequestReplyMarkup.md) |  | [optional] [default to undefined]

## Example

```typescript
import { SendStickerRequest } from 'tele_rest';

const instance: SendStickerRequest = {
    chat_id,
    sticker,
    business_connection_id,
    message_thread_id,
    emoji,
    disable_notification,
    protect_content,
    allow_paid_broadcast,
    message_effect_id,
    reply_parameters,
    reply_markup,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
