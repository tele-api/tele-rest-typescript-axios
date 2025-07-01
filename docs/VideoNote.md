# VideoNote

This object represents a [video message](https://telegram.org/blog/video-messages-and-telescope) (available in Telegram apps as of [v.4.0](https://telegram.org/blog/video-messages-and-telescope)).

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_id** | **string** | Identifier for this file, which can be used to download or reuse the file | [default to undefined]
**file_unique_id** | **string** | Unique identifier for this file, which is supposed to be the same over time and for different bots. Can\&#39;t be used to download or reuse the file. | [default to undefined]
**length** | **number** | Video width and height (diameter of the video message) as defined by the sender | [default to undefined]
**duration** | **number** | Duration of the video in seconds as defined by the sender | [default to undefined]
**thumbnail** | [**PhotoSize**](PhotoSize.md) |  | [optional] [default to undefined]
**file_size** | **number** | *Optional*. File size in bytes | [optional] [default to undefined]

## Example

```typescript
import { VideoNote } from 'tele_rest';

const instance: VideoNote = {
    file_id,
    file_unique_id,
    length,
    duration,
    thumbnail,
    file_size,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
