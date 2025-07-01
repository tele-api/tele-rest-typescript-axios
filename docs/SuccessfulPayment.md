# SuccessfulPayment

This object contains basic information about a successful payment. Note that if the buyer initiates a chargeback with the relevant payment provider following this transaction, the funds may be debited from your balance. This is outside of Telegram\'s control.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency** | **string** | Three-letter ISO 4217 [currency](https://core.telegram.org/bots/payments#supported-currencies) code, or “XTR” for payments in [Telegram Stars](https://t.me/BotNews/90) | [default to undefined]
**total_amount** | **number** | Total price in the *smallest units* of the currency (integer, **not** float/double). For example, for a price of &#x60;US$ 1.45&#x60; pass &#x60;amount &#x3D; 145&#x60;. See the *exp* parameter in [currencies.json](https://core.telegram.org/bots/payments/currencies.json), it shows the number of digits past the decimal point for each currency (2 for the majority of currencies). | [default to undefined]
**invoice_payload** | **string** | Bot-specified invoice payload | [default to undefined]
**telegram_payment_charge_id** | **string** | Telegram payment identifier | [default to undefined]
**provider_payment_charge_id** | **string** | Provider payment identifier | [default to undefined]
**subscription_expiration_date** | **number** | *Optional*. Expiration date of the subscription, in Unix time; for recurring payments only | [optional] [default to undefined]
**is_recurring** | **boolean** | *Optional*. True, if the payment is a recurring payment for a subscription | [optional] [default to true]
**is_first_recurring** | **boolean** | *Optional*. True, if the payment is the first payment for a subscription | [optional] [default to true]
**shipping_option_id** | **string** | *Optional*. Identifier of the shipping option chosen by the user | [optional] [default to undefined]
**order_info** | [**OrderInfo**](OrderInfo.md) |  | [optional] [default to undefined]

## Example

```typescript
import { SuccessfulPayment } from 'tele_rest';

const instance: SuccessfulPayment = {
    currency,
    total_amount,
    invoice_payload,
    telegram_payment_charge_id,
    provider_payment_charge_id,
    subscription_expiration_date,
    is_recurring,
    is_first_recurring,
    shipping_option_id,
    order_info,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
