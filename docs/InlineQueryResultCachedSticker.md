# InlineQueryResultCachedSticker

Represents a link to a sticker stored on the Telegram servers. By default, this sticker will be sent by the user. Alternatively, you can use *input\\_message\\_content* to send a message with the specified content instead of the sticker.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *sticker* | [default to 'sticker']
**id** | **string** | Unique identifier for this result, 1-64 bytes | [default to undefined]
**sticker_file_id** | **string** | A valid file identifier of the sticker | [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]
**input_message_content** | [**InputMessageContent**](InputMessageContent.md) |  | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultCachedSticker } from 'tele_rest';

const instance: InlineQueryResultCachedSticker = {
    type,
    id,
    sticker_file_id,
    reply_markup,
    input_message_content,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
