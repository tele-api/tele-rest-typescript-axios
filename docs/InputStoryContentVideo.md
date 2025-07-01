# InputStoryContentVideo

Describes a video to post as a story.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the content, must be *video* | [default to 'video']
**video** | **string** | The video to post as a story. The video must be of the size 720x1280, streamable, encoded with H.265 codec, with key frames added each second in the MPEG4 format, and must not exceed 30 MB. The video can\&#39;t be reused and can only be uploaded as a new file, so you can pass “attach://\\&lt;file\\_attach\\_name\\&gt;” if the video was uploaded using multipart/form-data under \\&lt;file\\_attach\\_name\\&gt;. [More information on Sending Files »](https://core.telegram.org/bots/api/#sending-files) | [default to undefined]
**duration** | **number** | *Optional*. Precise duration of the video in seconds; 0-60 | [optional] [default to undefined]
**cover_frame_timestamp** | **number** | *Optional*. Timestamp in seconds of the frame that will be used as the static cover for the story. Defaults to 0.0. | [optional] [default to undefined]
**is_animation** | **boolean** | *Optional*. Pass *True* if the video has no sound | [optional] [default to undefined]

## Example

```typescript
import { InputStoryContentVideo } from 'tele_rest';

const instance: InputStoryContentVideo = {
    type,
    video,
    duration,
    cover_frame_timestamp,
    is_animation,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
