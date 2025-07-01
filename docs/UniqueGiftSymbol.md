# UniqueGiftSymbol

This object describes the symbol shown on the pattern of a unique gift.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | Name of the symbol | [default to undefined]
**sticker** | [**Sticker**](Sticker.md) |  | [default to undefined]
**rarity_per_mille** | **number** | The number of unique gifts that receive this model for every 1000 gifts upgraded | [default to undefined]

## Example

```typescript
import { UniqueGiftSymbol } from 'tele_rest';

const instance: UniqueGiftSymbol = {
    name,
    sticker,
    rarity_per_mille,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
