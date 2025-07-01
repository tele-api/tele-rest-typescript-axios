# UniqueGift

This object describes a unique gift that was upgraded from a regular gift.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**base_name** | **string** | Human-readable name of the regular gift from which this unique gift was upgraded | [default to undefined]
**name** | **string** | Unique name of the gift. This name can be used in &#x60;https://t.me/nft/...&#x60; links and story areas | [default to undefined]
**number** | **number** | Unique number of the upgraded gift among gifts upgraded from the same regular gift | [default to undefined]
**model** | [**UniqueGiftModel**](UniqueGiftModel.md) |  | [default to undefined]
**symbol** | [**UniqueGiftSymbol**](UniqueGiftSymbol.md) |  | [default to undefined]
**backdrop** | [**UniqueGiftBackdrop**](UniqueGiftBackdrop.md) |  | [default to undefined]

## Example

```typescript
import { UniqueGift } from 'tele_rest';

const instance: UniqueGift = {
    base_name,
    name,
    number,
    model,
    symbol,
    backdrop,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
