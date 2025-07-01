# RefundedPayment

This object contains basic information about a refunded payment.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency** | **string** | Three-letter ISO 4217 [currency](https://core.telegram.org/bots/payments#supported-currencies) code, or “XTR” for payments in [Telegram Stars](https://t.me/BotNews/90). Currently, always “XTR” | [default to 'XTR']
**total_amount** | **number** | Total refunded price in the *smallest units* of the currency (integer, **not** float/double). For example, for a price of &#x60;US$ 1.45&#x60;, &#x60;total_amount &#x3D; 145&#x60;. See the *exp* parameter in [currencies.json](https://core.telegram.org/bots/payments/currencies.json), it shows the number of digits past the decimal point for each currency (2 for the majority of currencies). | [default to undefined]
**invoice_payload** | **string** | Bot-specified invoice payload | [default to undefined]
**telegram_payment_charge_id** | **string** | Telegram payment identifier | [default to undefined]
**provider_payment_charge_id** | **string** | *Optional*. Provider payment identifier | [optional] [default to undefined]

## Example

```typescript
import { RefundedPayment } from 'tele_rest';

const instance: RefundedPayment = {
    currency,
    total_amount,
    invoice_payload,
    telegram_payment_charge_id,
    provider_payment_charge_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
