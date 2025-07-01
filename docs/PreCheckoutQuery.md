# PreCheckoutQuery

This object contains information about an incoming pre-checkout query.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique query identifier | [default to undefined]
**from** | [**User**](User.md) |  | [default to undefined]
**currency** | **string** | Three-letter ISO 4217 [currency](https://core.telegram.org/bots/payments#supported-currencies) code, or “XTR” for payments in [Telegram Stars](https://t.me/BotNews/90) | [default to undefined]
**total_amount** | **number** | Total price in the *smallest units* of the currency (integer, **not** float/double). For example, for a price of &#x60;US$ 1.45&#x60; pass &#x60;amount &#x3D; 145&#x60;. See the *exp* parameter in [currencies.json](https://core.telegram.org/bots/payments/currencies.json), it shows the number of digits past the decimal point for each currency (2 for the majority of currencies). | [default to undefined]
**invoice_payload** | **string** | Bot-specified invoice payload | [default to undefined]
**shipping_option_id** | **string** | *Optional*. Identifier of the shipping option chosen by the user | [optional] [default to undefined]
**order_info** | [**OrderInfo**](OrderInfo.md) |  | [optional] [default to undefined]

## Example

```typescript
import { PreCheckoutQuery } from 'tele_rest';

const instance: PreCheckoutQuery = {
    id,
    from,
    currency,
    total_amount,
    invoice_payload,
    shipping_option_id,
    order_info,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
