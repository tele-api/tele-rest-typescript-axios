# ShippingOption

This object represents one shipping option.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Shipping option identifier | [default to undefined]
**title** | **string** | Option title | [default to undefined]
**prices** | [**Array&lt;LabeledPrice&gt;**](LabeledPrice.md) | List of price portions | [default to undefined]

## Example

```typescript
import { ShippingOption } from 'tele_rest';

const instance: ShippingOption = {
    id,
    title,
    prices,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
