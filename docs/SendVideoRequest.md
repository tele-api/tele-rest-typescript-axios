# SendVideoRequest

Request parameters for sendVideo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessageRequestChatId**](SendMessageRequestChatId.md) |  | [default to undefined]
**video** | **string** |  | [default to undefined]
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which the message will be sent | [optional] [default to undefined]
**message_thread_id** | **number** | Unique identifier for the target message thread (topic) of the forum; for forum supergroups only | [optional] [default to undefined]
**duration** | **number** | Duration of sent video in seconds | [optional] [default to undefined]
**width** | **number** | Video width | [optional] [default to undefined]
**height** | **number** | Video height | [optional] [default to undefined]
**thumbnail** | **string** |  | [optional] [default to undefined]
**cover** | **string** |  | [optional] [default to undefined]
**start_timestamp** | **number** | Start timestamp for the video in the message | [optional] [default to undefined]
**caption** | **string** | Video caption (may also be used when resending videos by *file\\_id*), 0-1024 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | Mode for parsing entities in the video caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | A JSON-serialized list of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**show_caption_above_media** | **boolean** | Pass *True*, if the caption must be shown above the message media | [optional] [default to undefined]
**has_spoiler** | **boolean** | Pass *True* if the video needs to be covered with a spoiler animation | [optional] [default to undefined]
**supports_streaming** | **boolean** | Pass *True* if the uploaded video is suitable for streaming | [optional] [default to undefined]
**disable_notification** | **boolean** | Sends the message [silently](https://telegram.org/blog/channels-2-0#silent-messages). Users will receive a notification with no sound. | [optional] [default to undefined]
**protect_content** | **boolean** | Protects the contents of the sent message from forwarding and saving | [optional] [default to undefined]
**allow_paid_broadcast** | **boolean** | Pass *True* to allow up to 1000 messages per second, ignoring [broadcasting limits](https://core.telegram.org/bots/faq#how-can-i-message-all-of-my-bot-39s-subscribers-at-once) for a fee of 0.1 Telegram Stars per message. The relevant Stars will be withdrawn from the bot\&#39;s balance | [optional] [default to undefined]
**message_effect_id** | **string** | Unique identifier of the message effect to be added to the message; for private chats only | [optional] [default to undefined]
**reply_parameters** | [**ReplyParameters**](ReplyParameters.md) |  | [optional] [default to undefined]
**reply_markup** | [**SendMessageRequestReplyMarkup**](SendMessageRequestReplyMarkup.md) |  | [optional] [default to undefined]

## Example

```typescript
import { SendVideoRequest } from 'tele_rest';

const instance: SendVideoRequest = {
    chat_id,
    video,
    business_connection_id,
    message_thread_id,
    duration,
    width,
    height,
    thumbnail,
    cover,
    start_timestamp,
    caption,
    parse_mode,
    caption_entities,
    show_caption_above_media,
    has_spoiler,
    supports_streaming,
    disable_notification,
    protect_content,
    allow_paid_broadcast,
    message_effect_id,
    reply_parameters,
    reply_markup,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
