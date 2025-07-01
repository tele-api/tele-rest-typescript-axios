# InlineQueryResultVideo

Represents a link to a page containing an embedded video player or a video file. By default, this video file will be sent by the user with an optional caption. Alternatively, you can use *input\\_message\\_content* to send a message with the specified content instead of the video.  If an InlineQueryResultVideo message contains an embedded video (e.g., YouTube), you **must** replace its content using *input\\_message\\_content*.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *video* | [default to 'video']
**id** | **string** | Unique identifier for this result, 1-64 bytes | [default to undefined]
**video_url** | **string** | A valid URL for the embedded video player or video file | [default to undefined]
**mime_type** | **string** | MIME type of the content of the video URL, “text/html” or “video/mp4” | [default to undefined]
**thumbnail_url** | **string** | URL of the thumbnail (JPEG only) for the video | [default to undefined]
**title** | **string** | Title for the result | [default to undefined]
**caption** | **string** | *Optional*. Caption of the video to be sent, 0-1024 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | *Optional*. Mode for parsing entities in the video caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. List of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**show_caption_above_media** | **boolean** | *Optional*. Pass *True*, if the caption must be shown above the message media | [optional] [default to undefined]
**video_width** | **number** | *Optional*. Video width | [optional] [default to undefined]
**video_height** | **number** | *Optional*. Video height | [optional] [default to undefined]
**video_duration** | **number** | *Optional*. Video duration in seconds | [optional] [default to undefined]
**description** | **string** | *Optional*. Short description of the result | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]
**input_message_content** | [**InputMessageContent**](InputMessageContent.md) |  | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultVideo } from 'tele_rest';

const instance: InlineQueryResultVideo = {
    type,
    id,
    video_url,
    mime_type,
    thumbnail_url,
    title,
    caption,
    parse_mode,
    caption_entities,
    show_caption_above_media,
    video_width,
    video_height,
    video_duration,
    description,
    reply_markup,
    input_message_content,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
