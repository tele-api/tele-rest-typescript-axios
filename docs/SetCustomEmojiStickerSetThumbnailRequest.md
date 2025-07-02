# SetCustomEmojiStickerSetThumbnailRequest

Request parameters for setCustomEmojiStickerSetThumbnail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | Sticker set name | [default to undefined]
**custom_emoji_id** | **string** | Custom emoji identifier of a sticker from the sticker set; pass an empty string to drop the thumbnail and use the first sticker as the thumbnail. | [optional] [default to undefined]

## Example

```typescript
import { SetCustomEmojiStickerSetThumbnailRequest } from 'tele_rest';

const instance: SetCustomEmojiStickerSetThumbnailRequest = {
    name,
    custom_emoji_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
