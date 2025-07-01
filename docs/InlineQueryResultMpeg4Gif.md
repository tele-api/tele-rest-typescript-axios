# InlineQueryResultMpeg4Gif

Represents a link to a video animation (H.264/MPEG-4 AVC video without sound). By default, this animated MPEG-4 file will be sent by the user with optional caption. Alternatively, you can use *input\\_message\\_content* to send a message with the specified content instead of the animation.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *mpeg4\\_gif* | [default to 'mpeg4_gif']
**id** | **string** | Unique identifier for this result, 1-64 bytes | [default to undefined]
**mpeg4_url** | **string** | A valid URL for the MPEG4 file | [default to undefined]
**thumbnail_url** | **string** | URL of the static (JPEG or GIF) or animated (MPEG4) thumbnail for the result | [default to undefined]
**mpeg4_width** | **number** | *Optional*. Video width | [optional] [default to undefined]
**mpeg4_height** | **number** | *Optional*. Video height | [optional] [default to undefined]
**mpeg4_duration** | **number** | *Optional*. Video duration in seconds | [optional] [default to undefined]
**thumbnail_mime_type** | **string** | *Optional*. MIME type of the thumbnail, must be one of “image/jpeg”, “image/gif”, or “video/mp4”. Defaults to “image/jpeg” | [optional] [default to ThumbnailMimeTypeEnum_ImageJpeg]
**title** | **string** | *Optional*. Title for the result | [optional] [default to undefined]
**caption** | **string** | *Optional*. Caption of the MPEG-4 file to be sent, 0-1024 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | *Optional*. Mode for parsing entities in the caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. List of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**show_caption_above_media** | **boolean** | *Optional*. Pass *True*, if the caption must be shown above the message media | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]
**input_message_content** | [**InputMessageContent**](InputMessageContent.md) |  | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultMpeg4Gif } from 'tele_rest';

const instance: InlineQueryResultMpeg4Gif = {
    type,
    id,
    mpeg4_url,
    thumbnail_url,
    mpeg4_width,
    mpeg4_height,
    mpeg4_duration,
    thumbnail_mime_type,
    title,
    caption,
    parse_mode,
    caption_entities,
    show_caption_above_media,
    reply_markup,
    input_message_content,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
