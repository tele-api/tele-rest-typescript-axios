# InlineQueryResult

This object represents one result of an inline query. Telegram clients currently support results of the following 20 types:  * [InlineQueryResultCachedAudio](https://core.telegram.org/bots/api/#inlinequeryresultcachedaudio) * [InlineQueryResultCachedDocument](https://core.telegram.org/bots/api/#inlinequeryresultcacheddocument) * [InlineQueryResultCachedGif](https://core.telegram.org/bots/api/#inlinequeryresultcachedgif) * [InlineQueryResultCachedMpeg4Gif](https://core.telegram.org/bots/api/#inlinequeryresultcachedmpeg4gif) * [InlineQueryResultCachedPhoto](https://core.telegram.org/bots/api/#inlinequeryresultcachedphoto) * [InlineQueryResultCachedSticker](https://core.telegram.org/bots/api/#inlinequeryresultcachedsticker) * [InlineQueryResultCachedVideo](https://core.telegram.org/bots/api/#inlinequeryresultcachedvideo) * [InlineQueryResultCachedVoice](https://core.telegram.org/bots/api/#inlinequeryresultcachedvoice) * [InlineQueryResultArticle](https://core.telegram.org/bots/api/#inlinequeryresultarticle) * [InlineQueryResultAudio](https://core.telegram.org/bots/api/#inlinequeryresultaudio) * [InlineQueryResultContact](https://core.telegram.org/bots/api/#inlinequeryresultcontact) * [InlineQueryResultGame](https://core.telegram.org/bots/api/#inlinequeryresultgame) * [InlineQueryResultDocument](https://core.telegram.org/bots/api/#inlinequeryresultdocument) * [InlineQueryResultGif](https://core.telegram.org/bots/api/#inlinequeryresultgif) * [InlineQueryResultLocation](https://core.telegram.org/bots/api/#inlinequeryresultlocation) * [InlineQueryResultMpeg4Gif](https://core.telegram.org/bots/api/#inlinequeryresultmpeg4gif) * [InlineQueryResultPhoto](https://core.telegram.org/bots/api/#inlinequeryresultphoto) * [InlineQueryResultVenue](https://core.telegram.org/bots/api/#inlinequeryresultvenue) * [InlineQueryResultVideo](https://core.telegram.org/bots/api/#inlinequeryresultvideo) * [InlineQueryResultVoice](https://core.telegram.org/bots/api/#inlinequeryresultvoice)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *voice* | [default to 'voice']
**id** | **string** | Unique identifier for this result, 1-64 bytes | [default to undefined]
**audio_file_id** | **string** | A valid file identifier for the audio file | [default to undefined]
**input_message_content** | [**InputMessageContent**](InputMessageContent.md) |  | [default to undefined]
**title** | **string** | Recording title | [default to undefined]
**document_file_id** | **string** | A valid file identifier for the file | [default to undefined]
**gif_file_id** | **string** | A valid file identifier for the GIF file | [default to undefined]
**mpeg4_file_id** | **string** | A valid file identifier for the MPEG4 file | [default to undefined]
**photo_file_id** | **string** | A valid file identifier of the photo | [default to undefined]
**sticker_file_id** | **string** | A valid file identifier of the sticker | [default to undefined]
**video_file_id** | **string** | A valid file identifier for the video file | [default to undefined]
**voice_file_id** | **string** | A valid file identifier for the voice message | [default to undefined]
**thumbnail_url** | **string** | URL of the thumbnail (JPEG only) for the video | [default to undefined]
**audio_url** | **string** | A valid URL for the audio file | [default to undefined]
**phone_number** | **string** | Contact\&#39;s phone number | [default to undefined]
**first_name** | **string** | Contact\&#39;s first name | [default to undefined]
**game_short_name** | **string** | Short name of the game | [default to undefined]
**document_url** | **string** | A valid URL for the file | [default to undefined]
**mime_type** | **string** | MIME type of the content of the video URL, “text/html” or “video/mp4” | [default to undefined]
**gif_url** | **string** | A valid URL for the GIF file | [default to undefined]
**latitude** | **number** | Latitude of the venue location in degrees | [default to undefined]
**longitude** | **number** | Longitude of the venue location in degrees | [default to undefined]
**mpeg4_url** | **string** | A valid URL for the MPEG4 file | [default to undefined]
**photo_url** | **string** | A valid URL of the photo. Photo must be in **JPEG** format. Photo size must not exceed 5MB | [default to undefined]
**address** | **string** | Address of the venue | [default to undefined]
**video_url** | **string** | A valid URL for the embedded video player or video file | [default to undefined]
**voice_url** | **string** | A valid URL for the voice recording | [default to undefined]
**caption** | **string** | *Optional*. Caption, 0-1024 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | *Optional*. Mode for parsing entities in the voice message caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. List of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]
**description** | **string** | *Optional*. Short description of the result | [optional] [default to undefined]
**show_caption_above_media** | **boolean** | *Optional*. Pass *True*, if the caption must be shown above the message media | [optional] [default to undefined]
**url** | **string** | *Optional*. URL of the result | [optional] [default to undefined]
**thumbnail_width** | **number** | *Optional*. Thumbnail width | [optional] [default to undefined]
**thumbnail_height** | **number** | *Optional*. Thumbnail height | [optional] [default to undefined]
**performer** | **string** | *Optional*. Performer | [optional] [default to undefined]
**audio_duration** | **number** | *Optional*. Audio duration in seconds | [optional] [default to undefined]
**last_name** | **string** | *Optional*. Contact\&#39;s last name | [optional] [default to undefined]
**vcard** | **string** | *Optional*. Additional data about the contact in the form of a [vCard](https://en.wikipedia.org/wiki/VCard), 0-2048 bytes | [optional] [default to undefined]
**gif_width** | **number** | *Optional*. Width of the GIF | [optional] [default to undefined]
**gif_height** | **number** | *Optional*. Height of the GIF | [optional] [default to undefined]
**gif_duration** | **number** | *Optional*. Duration of the GIF in seconds | [optional] [default to undefined]
**thumbnail_mime_type** | **string** | *Optional*. MIME type of the thumbnail, must be one of “image/jpeg”, “image/gif”, or “video/mp4”. Defaults to “image/jpeg” | [optional] [default to ThumbnailMimeTypeEnum_ImageJpeg]
**horizontal_accuracy** | **number** | *Optional*. The radius of uncertainty for the location, measured in meters; 0-1500 | [optional] [default to undefined]
**live_period** | **number** | *Optional*. Period in seconds during which the location can be updated, should be between 60 and 86400, or 0x7FFFFFFF for live locations that can be edited indefinitely. | [optional] [default to undefined]
**heading** | **number** | *Optional*. For live locations, a direction in which the user is moving, in degrees. Must be between 1 and 360 if specified. | [optional] [default to undefined]
**proximity_alert_radius** | **number** | *Optional*. For live locations, a maximum distance for proximity alerts about approaching another chat member, in meters. Must be between 1 and 100000 if specified. | [optional] [default to undefined]
**mpeg4_width** | **number** | *Optional*. Video width | [optional] [default to undefined]
**mpeg4_height** | **number** | *Optional*. Video height | [optional] [default to undefined]
**mpeg4_duration** | **number** | *Optional*. Video duration in seconds | [optional] [default to undefined]
**photo_width** | **number** | *Optional*. Width of the photo | [optional] [default to undefined]
**photo_height** | **number** | *Optional*. Height of the photo | [optional] [default to undefined]
**foursquare_id** | **string** | *Optional*. Foursquare identifier of the venue if known | [optional] [default to undefined]
**foursquare_type** | **string** | *Optional*. Foursquare type of the venue, if known. (For example, “arts\\_entertainment/default”, “arts\\_entertainment/aquarium” or “food/icecream”.) | [optional] [default to undefined]
**google_place_id** | **string** | *Optional*. Google Places identifier of the venue | [optional] [default to undefined]
**google_place_type** | **string** | *Optional*. Google Places type of the venue. (See [supported types](https://developers.google.com/places/web-service/supported_types).) | [optional] [default to undefined]
**video_width** | **number** | *Optional*. Video width | [optional] [default to undefined]
**video_height** | **number** | *Optional*. Video height | [optional] [default to undefined]
**video_duration** | **number** | *Optional*. Video duration in seconds | [optional] [default to undefined]
**voice_duration** | **number** | *Optional*. Recording duration in seconds | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResult } from 'tele_rest';

const instance: InlineQueryResult = {
    type,
    id,
    audio_file_id,
    input_message_content,
    title,
    document_file_id,
    gif_file_id,
    mpeg4_file_id,
    photo_file_id,
    sticker_file_id,
    video_file_id,
    voice_file_id,
    thumbnail_url,
    audio_url,
    phone_number,
    first_name,
    game_short_name,
    document_url,
    mime_type,
    gif_url,
    latitude,
    longitude,
    mpeg4_url,
    photo_url,
    address,
    video_url,
    voice_url,
    caption,
    parse_mode,
    caption_entities,
    reply_markup,
    description,
    show_caption_above_media,
    url,
    thumbnail_width,
    thumbnail_height,
    performer,
    audio_duration,
    last_name,
    vcard,
    gif_width,
    gif_height,
    gif_duration,
    thumbnail_mime_type,
    horizontal_accuracy,
    live_period,
    heading,
    proximity_alert_radius,
    mpeg4_width,
    mpeg4_height,
    mpeg4_duration,
    photo_width,
    photo_height,
    foursquare_id,
    foursquare_type,
    google_place_id,
    google_place_type,
    video_width,
    video_height,
    video_duration,
    voice_duration,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
