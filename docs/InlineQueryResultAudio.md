# InlineQueryResultAudio

Represents a link to an MP3 audio file. By default, this audio file will be sent by the user. Alternatively, you can use *input\\_message\\_content* to send a message with the specified content instead of the audio.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *audio* | [default to 'audio']
**id** | **string** | Unique identifier for this result, 1-64 bytes | [default to undefined]
**audio_url** | **string** | A valid URL for the audio file | [default to undefined]
**title** | **string** | Title | [default to undefined]
**caption** | **string** | *Optional*. Caption, 0-1024 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | *Optional*. Mode for parsing entities in the audio caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. List of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**performer** | **string** | *Optional*. Performer | [optional] [default to undefined]
**audio_duration** | **number** | *Optional*. Audio duration in seconds | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]
**input_message_content** | [**InputMessageContent**](InputMessageContent.md) |  | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultAudio } from 'tele_rest';

const instance: InlineQueryResultAudio = {
    type,
    id,
    audio_url,
    title,
    caption,
    parse_mode,
    caption_entities,
    performer,
    audio_duration,
    reply_markup,
    input_message_content,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
