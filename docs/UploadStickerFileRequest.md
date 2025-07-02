# UploadStickerFileRequest

Request parameters for uploadStickerFile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **number** | User identifier of sticker file owner | [default to undefined]
**sticker** | **any** |  | [default to undefined]
**sticker_format** | **string** | Format of the sticker, must be one of “static”, “animated”, “video” | [default to undefined]

## Example

```typescript
import { UploadStickerFileRequest } from 'tele_rest';

const instance: UploadStickerFileRequest = {
    user_id,
    sticker,
    sticker_format,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
