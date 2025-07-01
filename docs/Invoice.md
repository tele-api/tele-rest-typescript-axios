# Invoice

This object contains basic information about an invoice.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **string** | Product name | [default to undefined]
**description** | **string** | Product description | [default to undefined]
**start_parameter** | **string** | Unique bot deep-linking parameter that can be used to generate this invoice | [default to undefined]
**currency** | **string** | Three-letter ISO 4217 [currency](https://core.telegram.org/bots/payments#supported-currencies) code, or “XTR” for payments in [Telegram Stars](https://t.me/BotNews/90) | [default to undefined]
**total_amount** | **number** | Total price in the *smallest units* of the currency (integer, **not** float/double). For example, for a price of &#x60;US$ 1.45&#x60; pass &#x60;amount &#x3D; 145&#x60;. See the *exp* parameter in [currencies.json](https://core.telegram.org/bots/payments/currencies.json), it shows the number of digits past the decimal point for each currency (2 for the majority of currencies). | [default to undefined]

## Example

```typescript
import { Invoice } from 'tele_rest';

const instance: Invoice = {
    title,
    description,
    start_parameter,
    currency,
    total_amount,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
