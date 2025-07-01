# InlineQueryResultCachedVideo

Represents a link to a video file stored on the Telegram servers. By default, this video file will be sent by the user with an optional caption. Alternatively, you can use *input\\_message\\_content* to send a message with the specified content instead of the video.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *video* | [default to 'video']
**id** | **string** | Unique identifier for this result, 1-64 bytes | [default to undefined]
**video_file_id** | **string** | A valid file identifier for the video file | [default to undefined]
**title** | **string** | Title for the result | [default to undefined]
**description** | **string** | *Optional*. Short description of the result | [optional] [default to undefined]
**caption** | **string** | *Optional*. Caption of the video to be sent, 0-1024 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | *Optional*. Mode for parsing entities in the video caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. List of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**show_caption_above_media** | **boolean** | *Optional*. Pass *True*, if the caption must be shown above the message media | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]
**input_message_content** | [**InputMessageContent**](InputMessageContent.md) |  | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultCachedVideo } from 'tele_rest';

const instance: InlineQueryResultCachedVideo = {
    type,
    id,
    video_file_id,
    title,
    description,
    caption,
    parse_mode,
    caption_entities,
    show_caption_above_media,
    reply_markup,
    input_message_content,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
