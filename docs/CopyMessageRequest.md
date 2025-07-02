# CopyMessageRequest

Request parameters for copyMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessageRequestChatId**](SendMessageRequestChatId.md) |  | [default to undefined]
**from_chat_id** | [**ForwardMessageRequestFromChatId**](ForwardMessageRequestFromChatId.md) |  | [default to undefined]
**message_id** | **number** | Message identifier in the chat specified in *from\\_chat\\_id* | [default to undefined]
**message_thread_id** | **number** | Unique identifier for the target message thread (topic) of the forum; for forum supergroups only | [optional] [default to undefined]
**video_start_timestamp** | **number** | New start timestamp for the copied video in the message | [optional] [default to undefined]
**caption** | **string** | New caption for media, 0-1024 characters after entities parsing. If not specified, the original caption is kept | [optional] [default to undefined]
**parse_mode** | **string** | Mode for parsing entities in the new caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | A JSON-serialized list of special entities that appear in the new caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**show_caption_above_media** | **boolean** | Pass *True*, if the caption must be shown above the message media. Ignored if a new caption isn\&#39;t specified. | [optional] [default to undefined]
**disable_notification** | **boolean** | Sends the message [silently](https://telegram.org/blog/channels-2-0#silent-messages). Users will receive a notification with no sound. | [optional] [default to undefined]
**protect_content** | **boolean** | Protects the contents of the sent message from forwarding and saving | [optional] [default to undefined]
**allow_paid_broadcast** | **boolean** | Pass *True* to allow up to 1000 messages per second, ignoring [broadcasting limits](https://core.telegram.org/bots/faq#how-can-i-message-all-of-my-bot-39s-subscribers-at-once) for a fee of 0.1 Telegram Stars per message. The relevant Stars will be withdrawn from the bot\&#39;s balance | [optional] [default to undefined]
**reply_parameters** | [**ReplyParameters**](ReplyParameters.md) |  | [optional] [default to undefined]
**reply_markup** | [**SendMessageRequestReplyMarkup**](SendMessageRequestReplyMarkup.md) |  | [optional] [default to undefined]

## Example

```typescript
import { CopyMessageRequest } from 'tele_rest';

const instance: CopyMessageRequest = {
    chat_id,
    from_chat_id,
    message_id,
    message_thread_id,
    video_start_timestamp,
    caption,
    parse_mode,
    caption_entities,
    show_caption_above_media,
    disable_notification,
    protect_content,
    allow_paid_broadcast,
    reply_parameters,
    reply_markup,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
