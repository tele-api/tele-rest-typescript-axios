# UniqueGiftBackdrop

This object describes the backdrop of a unique gift.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | Name of the backdrop | [default to undefined]
**colors** | [**UniqueGiftBackdropColors**](UniqueGiftBackdropColors.md) |  | [default to undefined]
**rarity_per_mille** | **number** | The number of unique gifts that receive this backdrop for every 1000 gifts upgraded | [default to undefined]

## Example

```typescript
import { UniqueGiftBackdrop } from 'tele_rest';

const instance: UniqueGiftBackdrop = {
    name,
    colors,
    rarity_per_mille,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
