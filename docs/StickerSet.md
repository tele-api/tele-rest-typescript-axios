# StickerSet

This object represents a sticker set.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | Sticker set name | [default to undefined]
**title** | **string** | Sticker set title | [default to undefined]
**sticker_type** | **string** | Type of stickers in the set, currently one of “regular”, “mask”, “custom\\_emoji” | [default to undefined]
**stickers** | [**Array&lt;Sticker&gt;**](Sticker.md) | List of all set stickers | [default to undefined]
**thumbnail** | [**PhotoSize**](PhotoSize.md) |  | [optional] [default to undefined]

## Example

```typescript
import { StickerSet } from 'tele_rest';

const instance: StickerSet = {
    name,
    title,
    sticker_type,
    stickers,
    thumbnail,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
