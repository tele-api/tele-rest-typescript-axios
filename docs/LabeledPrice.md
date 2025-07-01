# LabeledPrice

This object represents a portion of the price for goods or services.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**label** | **string** | Portion label | [default to undefined]
**amount** | **number** | Price of the product in the *smallest units* of the [currency](https://core.telegram.org/bots/payments#supported-currencies) (integer, **not** float/double). For example, for a price of &#x60;US$ 1.45&#x60; pass &#x60;amount &#x3D; 145&#x60;. See the *exp* parameter in [currencies.json](https://core.telegram.org/bots/payments/currencies.json), it shows the number of digits past the decimal point for each currency (2 for the majority of currencies). | [default to undefined]

## Example

```typescript
import { LabeledPrice } from 'tele_rest';

const instance: LabeledPrice = {
    label,
    amount,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
