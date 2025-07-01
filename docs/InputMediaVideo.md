# InputMediaVideo

Represents a video to be sent.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *video* | [default to 'video']
**media** | **string** | File to send. Pass a file\\_id to send a file that exists on the Telegram servers (recommended), pass an HTTP URL for Telegram to get a file from the Internet, or pass “attach://\\&lt;file\\_attach\\_name\\&gt;” to upload a new one using multipart/form-data under \\&lt;file\\_attach\\_name\\&gt; name. [More information on Sending Files »](https://core.telegram.org/bots/api/#sending-files) | [default to undefined]
**thumbnail** | **string** | *Optional*. Thumbnail of the file sent; can be ignored if thumbnail generation for the file is supported server-side. The thumbnail should be in JPEG format and less than 200 kB in size. A thumbnail\&#39;s width and height should not exceed 320. Ignored if the file is not uploaded using multipart/form-data. Thumbnails can\&#39;t be reused and can be only uploaded as a new file, so you can pass “attach://\\&lt;file\\_attach\\_name\\&gt;” if the thumbnail was uploaded using multipart/form-data under \\&lt;file\\_attach\\_name\\&gt;. [More information on Sending Files »](https://core.telegram.org/bots/api/#sending-files) | [optional] [default to undefined]
**cover** | **string** | *Optional*. Cover for the video in the message. Pass a file\\_id to send a file that exists on the Telegram servers (recommended), pass an HTTP URL for Telegram to get a file from the Internet, or pass “attach://\\&lt;file\\_attach\\_name\\&gt;” to upload a new one using multipart/form-data under \\&lt;file\\_attach\\_name\\&gt; name. [More information on Sending Files »](https://core.telegram.org/bots/api/#sending-files) | [optional] [default to undefined]
**start_timestamp** | **number** | *Optional*. Start timestamp for the video in the message | [optional] [default to undefined]
**caption** | **string** | *Optional*. Caption of the video to be sent, 0-1024 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | *Optional*. Mode for parsing entities in the video caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. List of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**show_caption_above_media** | **boolean** | *Optional*. Pass *True*, if the caption must be shown above the message media | [optional] [default to undefined]
**width** | **number** | *Optional*. Video width | [optional] [default to undefined]
**height** | **number** | *Optional*. Video height | [optional] [default to undefined]
**duration** | **number** | *Optional*. Video duration in seconds | [optional] [default to undefined]
**supports_streaming** | **boolean** | *Optional*. Pass *True* if the uploaded video is suitable for streaming | [optional] [default to undefined]
**has_spoiler** | **boolean** | *Optional*. Pass *True* if the video needs to be covered with a spoiler animation | [optional] [default to undefined]

## Example

```typescript
import { InputMediaVideo } from 'tele_rest';

const instance: InputMediaVideo = {
    type,
    media,
    thumbnail,
    cover,
    start_timestamp,
    caption,
    parse_mode,
    caption_entities,
    show_caption_above_media,
    width,
    height,
    duration,
    supports_streaming,
    has_spoiler,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
