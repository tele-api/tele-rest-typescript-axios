# EditMessageCaptionPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which the message to be edited was sent | [optional] [default to undefined]
**chat_id** | [**EditMessageTextPostRequestChatId**](EditMessageTextPostRequestChatId.md) |  | [optional] [default to undefined]
**message_id** | **number** | Required if *inline\\_message\\_id* is not specified. Identifier of the message to edit | [optional] [default to undefined]
**inline_message_id** | **string** | Required if *chat\\_id* and *message\\_id* are not specified. Identifier of the inline message | [optional] [default to undefined]
**caption** | **string** | New caption of the message, 0-1024 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | Mode for parsing entities in the message caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | A JSON-serialized list of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**show_caption_above_media** | **boolean** | Pass *True*, if the caption must be shown above the message media. Supported only for animation, photo and video messages. | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]

## Example

```typescript
import { EditMessageCaptionPostRequest } from 'tele_rest';

const instance: EditMessageCaptionPostRequest = {
    business_connection_id,
    chat_id,
    message_id,
    inline_message_id,
    caption,
    parse_mode,
    caption_entities,
    show_caption_above_media,
    reply_markup,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
