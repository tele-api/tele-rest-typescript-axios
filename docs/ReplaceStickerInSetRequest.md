# ReplaceStickerInSetRequest

Request parameters for replaceStickerInSet

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **number** | User identifier of the sticker set owner | [default to undefined]
**name** | **string** | Sticker set name | [default to undefined]
**old_sticker** | **string** | File identifier of the replaced sticker | [default to undefined]
**sticker** | [**InputSticker**](InputSticker.md) |  | [default to undefined]

## Example

```typescript
import { ReplaceStickerInSetRequest } from 'tele_rest';

const instance: ReplaceStickerInSetRequest = {
    user_id,
    name,
    old_sticker,
    sticker,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
