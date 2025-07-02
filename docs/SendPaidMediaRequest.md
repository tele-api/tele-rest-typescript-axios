# SendPaidMediaRequest

Request parameters for sendPaidMedia

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendPaidMediaRequestChatId**](SendPaidMediaRequestChatId.md) |  | [default to undefined]
**star_count** | **number** | The number of Telegram Stars that must be paid to buy access to the media; 1-10000 | [default to undefined]
**media** | [**Array&lt;InputPaidMedia&gt;**](InputPaidMedia.md) | A JSON-serialized array describing the media to be sent; up to 10 items | [default to undefined]
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which the message will be sent | [optional] [default to undefined]
**payload** | **string** | Bot-defined paid media payload, 0-128 bytes. This will not be displayed to the user, use it for your internal processes. | [optional] [default to undefined]
**caption** | **string** | Media caption, 0-1024 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | Mode for parsing entities in the media caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | A JSON-serialized list of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**show_caption_above_media** | **boolean** | Pass *True*, if the caption must be shown above the message media | [optional] [default to undefined]
**disable_notification** | **boolean** | Sends the message [silently](https://telegram.org/blog/channels-2-0#silent-messages). Users will receive a notification with no sound. | [optional] [default to undefined]
**protect_content** | **boolean** | Protects the contents of the sent message from forwarding and saving | [optional] [default to undefined]
**allow_paid_broadcast** | **boolean** | Pass *True* to allow up to 1000 messages per second, ignoring [broadcasting limits](https://core.telegram.org/bots/faq#how-can-i-message-all-of-my-bot-39s-subscribers-at-once) for a fee of 0.1 Telegram Stars per message. The relevant Stars will be withdrawn from the bot\&#39;s balance | [optional] [default to undefined]
**reply_parameters** | [**ReplyParameters**](ReplyParameters.md) |  | [optional] [default to undefined]
**reply_markup** | [**SendMessageRequestReplyMarkup**](SendMessageRequestReplyMarkup.md) |  | [optional] [default to undefined]

## Example

```typescript
import { SendPaidMediaRequest } from 'tele_rest';

const instance: SendPaidMediaRequest = {
    chat_id,
    star_count,
    media,
    business_connection_id,
    payload,
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
