# SetStickerSetThumbnailRequest

Request parameters for setStickerSetThumbnail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | Sticker set name | [default to undefined]
**user_id** | **number** | User identifier of the sticker set owner | [default to undefined]
**format** | **string** | Format of the thumbnail, must be one of “static” for a **.WEBP** or **.PNG** image, “animated” for a **.TGS** animation, or “video” for a **.WEBM** video | [default to undefined]
**thumbnail** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { SetStickerSetThumbnailRequest } from 'tele_rest';

const instance: SetStickerSetThumbnailRequest = {
    name,
    user_id,
    format,
    thumbnail,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
