# InlineQueryResultPhoto

Represents a link to a photo. By default, this photo will be sent by the user with optional caption. Alternatively, you can use *input\\_message\\_content* to send a message with the specified content instead of the photo.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *photo* | [default to 'photo']
**id** | **string** | Unique identifier for this result, 1-64 bytes | [default to undefined]
**photo_url** | **string** | A valid URL of the photo. Photo must be in **JPEG** format. Photo size must not exceed 5MB | [default to undefined]
**thumbnail_url** | **string** | URL of the thumbnail for the photo | [default to undefined]
**photo_width** | **number** | *Optional*. Width of the photo | [optional] [default to undefined]
**photo_height** | **number** | *Optional*. Height of the photo | [optional] [default to undefined]
**title** | **string** | *Optional*. Title for the result | [optional] [default to undefined]
**description** | **string** | *Optional*. Short description of the result | [optional] [default to undefined]
**caption** | **string** | *Optional*. Caption of the photo to be sent, 0-1024 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | *Optional*. Mode for parsing entities in the photo caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. List of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**show_caption_above_media** | **boolean** | *Optional*. Pass *True*, if the caption must be shown above the message media | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]
**input_message_content** | [**InputMessageContent**](InputMessageContent.md) |  | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultPhoto } from 'tele_rest';

const instance: InlineQueryResultPhoto = {
    type,
    id,
    photo_url,
    thumbnail_url,
    photo_width,
    photo_height,
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
