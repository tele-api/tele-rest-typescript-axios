# EditMessageTextRequest

Request parameters for editMessageText

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **string** | New text of the message, 1-4096 characters after entities parsing | [default to undefined]
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which the message to be edited was sent | [optional] [default to undefined]
**chat_id** | [**EditMessageTextRequestChatId**](EditMessageTextRequestChatId.md) |  | [optional] [default to undefined]
**message_id** | **number** | Required if *inline\\_message\\_id* is not specified. Identifier of the message to edit | [optional] [default to undefined]
**inline_message_id** | **string** | Required if *chat\\_id* and *message\\_id* are not specified. Identifier of the inline message | [optional] [default to undefined]
**parse_mode** | **string** | Mode for parsing entities in the message text. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | A JSON-serialized list of special entities that appear in message text, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**link_preview_options** | [**LinkPreviewOptions**](LinkPreviewOptions.md) |  | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]

## Example

```typescript
import { EditMessageTextRequest } from 'tele_rest';

const instance: EditMessageTextRequest = {
    text,
    business_connection_id,
    chat_id,
    message_id,
    inline_message_id,
    parse_mode,
    entities,
    link_preview_options,
    reply_markup,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
