# InlineQueryResultCachedVoice

Represents a link to a voice message stored on the Telegram servers. By default, this voice message will be sent by the user. Alternatively, you can use *input\\_message\\_content* to send a message with the specified content instead of the voice message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *voice* | [default to 'voice']
**id** | **string** | Unique identifier for this result, 1-64 bytes | [default to undefined]
**voice_file_id** | **string** | A valid file identifier for the voice message | [default to undefined]
**title** | **string** | Voice message title | [default to undefined]
**caption** | **string** | *Optional*. Caption, 0-1024 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | *Optional*. Mode for parsing entities in the voice message caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. List of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]
**input_message_content** | [**InputMessageContent**](InputMessageContent.md) |  | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultCachedVoice } from 'tele_rest';

const instance: InlineQueryResultCachedVoice = {
    type,
    id,
    voice_file_id,
    title,
    caption,
    parse_mode,
    caption_entities,
    reply_markup,
    input_message_content,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
