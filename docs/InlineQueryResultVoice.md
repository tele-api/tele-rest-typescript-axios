# InlineQueryResultVoice

Represents a link to a voice recording in an .OGG container encoded with OPUS. By default, this voice recording will be sent by the user. Alternatively, you can use *input\\_message\\_content* to send a message with the specified content instead of the the voice message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *voice* | [default to 'voice']
**id** | **string** | Unique identifier for this result, 1-64 bytes | [default to undefined]
**voice_url** | **string** | A valid URL for the voice recording | [default to undefined]
**title** | **string** | Recording title | [default to undefined]
**caption** | **string** | *Optional*. Caption, 0-1024 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | *Optional*. Mode for parsing entities in the voice message caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. List of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**voice_duration** | **number** | *Optional*. Recording duration in seconds | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]
**input_message_content** | [**InputMessageContent**](InputMessageContent.md) |  | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultVoice } from 'tele_rest';

const instance: InlineQueryResultVoice = {
    type,
    id,
    voice_url,
    title,
    caption,
    parse_mode,
    caption_entities,
    voice_duration,
    reply_markup,
    input_message_content,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
