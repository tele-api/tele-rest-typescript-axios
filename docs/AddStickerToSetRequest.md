# AddStickerToSetRequest

Request parameters for addStickerToSet

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **number** | User identifier of sticker set owner | [default to undefined]
**name** | **string** | Sticker set name | [default to undefined]
**sticker** | [**InputSticker**](InputSticker.md) |  | [default to undefined]

## Example

```typescript
import { AddStickerToSetRequest } from 'tele_rest';

const instance: AddStickerToSetRequest = {
    user_id,
    name,
    sticker,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
