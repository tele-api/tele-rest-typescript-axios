# CreateNewStickerSetRequest

Request parameters for createNewStickerSet

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **number** | User identifier of created sticker set owner | [default to undefined]
**name** | **string** | Short name of sticker set, to be used in &#x60;t.me/addstickers/&#x60; URLs (e.g., *animals*). Can contain only English letters, digits and underscores. Must begin with a letter, can\&#39;t contain consecutive underscores and must end in &#x60;\&quot;_by_&lt;bot_username&gt;\&quot;&#x60;. &#x60;&lt;bot_username&gt;&#x60; is case insensitive. 1-64 characters. | [default to undefined]
**title** | **string** | Sticker set title, 1-64 characters | [default to undefined]
**stickers** | [**Array&lt;InputSticker&gt;**](InputSticker.md) | A JSON-serialized list of 1-50 initial stickers to be added to the sticker set | [default to undefined]
**sticker_type** | **string** | Type of stickers in the set, pass “regular”, “mask”, or “custom\\_emoji”. By default, a regular sticker set is created. | [optional] [default to undefined]
**needs_repainting** | **boolean** | Pass *True* if stickers in the sticker set must be repainted to the color of text when used in messages, the accent color if used as emoji status, white on chat photos, or another appropriate color based on context; for custom emoji sticker sets only | [optional] [default to undefined]

## Example

```typescript
import { CreateNewStickerSetRequest } from 'tele_rest';

const instance: CreateNewStickerSetRequest = {
    user_id,
    name,
    title,
    stickers,
    sticker_type,
    needs_repainting,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
