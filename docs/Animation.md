# Animation

This object represents an animation file (GIF or H.264/MPEG-4 AVC video without sound).

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_id** | **string** | Identifier for this file, which can be used to download or reuse the file | [default to undefined]
**file_unique_id** | **string** | Unique identifier for this file, which is supposed to be the same over time and for different bots. Can\&#39;t be used to download or reuse the file. | [default to undefined]
**width** | **number** | Video width as defined by the sender | [default to undefined]
**height** | **number** | Video height as defined by the sender | [default to undefined]
**duration** | **number** | Duration of the video in seconds as defined by the sender | [default to undefined]
**thumbnail** | [**PhotoSize**](PhotoSize.md) |  | [optional] [default to undefined]
**file_name** | **string** | *Optional*. Original animation filename as defined by the sender | [optional] [default to undefined]
**mime_type** | **string** | *Optional*. MIME type of the file as defined by the sender | [optional] [default to undefined]
**file_size** | **number** | *Optional*. File size in bytes. It can be bigger than 2^31 and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a signed 64-bit integer or double-precision float type are safe for storing this value. | [optional] [default to undefined]

## Example

```typescript
import { Animation } from 'tele_rest';

const instance: Animation = {
    file_id,
    file_unique_id,
    width,
    height,
    duration,
    thumbnail,
    file_name,
    mime_type,
    file_size,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
