# InputInvoiceMessageContent

Represents the [content](https://core.telegram.org/bots/api/#inputmessagecontent) of an invoice message to be sent as the result of an inline query.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **string** | Product name, 1-32 characters | [default to undefined]
**description** | **string** | Product description, 1-255 characters | [default to undefined]
**payload** | **string** | Bot-defined invoice payload, 1-128 bytes. This will not be displayed to the user, use it for your internal processes. | [default to undefined]
**currency** | **string** | Three-letter ISO 4217 currency code, see [more on currencies](https://core.telegram.org/bots/payments#supported-currencies). Pass “XTR” for payments in [Telegram Stars](https://t.me/BotNews/90). | [default to undefined]
**prices** | [**Array&lt;LabeledPrice&gt;**](LabeledPrice.md) | Price breakdown, a JSON-serialized list of components (e.g. product price, tax, discount, delivery cost, delivery tax, bonus, etc.). Must contain exactly one item for payments in [Telegram Stars](https://t.me/BotNews/90). | [default to undefined]
**provider_token** | **string** | *Optional*. Payment provider token, obtained via [@BotFather](https://t.me/botfather). Pass an empty string for payments in [Telegram Stars](https://t.me/BotNews/90). | [optional] [default to undefined]
**max_tip_amount** | **number** | *Optional*. The maximum accepted amount for tips in the *smallest units* of the currency (integer, **not** float/double). For example, for a maximum tip of &#x60;US$ 1.45&#x60; pass &#x60;max_tip_amount &#x3D; 145&#x60;. See the *exp* parameter in [currencies.json](https://core.telegram.org/bots/payments/currencies.json), it shows the number of digits past the decimal point for each currency (2 for the majority of currencies). Defaults to 0. Not supported for payments in [Telegram Stars](https://t.me/BotNews/90). | [optional] [default to 0]
**suggested_tip_amounts** | **Array&lt;number&gt;** | *Optional*. A JSON-serialized array of suggested amounts of tip in the *smallest units* of the currency (integer, **not** float/double). At most 4 suggested tip amounts can be specified. The suggested tip amounts must be positive, passed in a strictly increased order and must not exceed *max\\_tip\\_amount*. | [optional] [default to undefined]
**provider_data** | **string** | *Optional*. A JSON-serialized object for data about the invoice, which will be shared with the payment provider. A detailed description of the required fields should be provided by the payment provider. | [optional] [default to undefined]
**photo_url** | **string** | *Optional*. URL of the product photo for the invoice. Can be a photo of the goods or a marketing image for a service. | [optional] [default to undefined]
**photo_size** | **number** | *Optional*. Photo size in bytes | [optional] [default to undefined]
**photo_width** | **number** | *Optional*. Photo width | [optional] [default to undefined]
**photo_height** | **number** | *Optional*. Photo height | [optional] [default to undefined]
**need_name** | **boolean** | *Optional*. Pass *True* if you require the user\&#39;s full name to complete the order. Ignored for payments in [Telegram Stars](https://t.me/BotNews/90). | [optional] [default to undefined]
**need_phone_number** | **boolean** | *Optional*. Pass *True* if you require the user\&#39;s phone number to complete the order. Ignored for payments in [Telegram Stars](https://t.me/BotNews/90). | [optional] [default to undefined]
**need_email** | **boolean** | *Optional*. Pass *True* if you require the user\&#39;s email address to complete the order. Ignored for payments in [Telegram Stars](https://t.me/BotNews/90). | [optional] [default to undefined]
**need_shipping_address** | **boolean** | *Optional*. Pass *True* if you require the user\&#39;s shipping address to complete the order. Ignored for payments in [Telegram Stars](https://t.me/BotNews/90). | [optional] [default to undefined]
**send_phone_number_to_provider** | **boolean** | *Optional*. Pass *True* if the user\&#39;s phone number should be sent to the provider. Ignored for payments in [Telegram Stars](https://t.me/BotNews/90). | [optional] [default to undefined]
**send_email_to_provider** | **boolean** | *Optional*. Pass *True* if the user\&#39;s email address should be sent to the provider. Ignored for payments in [Telegram Stars](https://t.me/BotNews/90). | [optional] [default to undefined]
**is_flexible** | **boolean** | *Optional*. Pass *True* if the final price depends on the shipping method. Ignored for payments in [Telegram Stars](https://t.me/BotNews/90). | [optional] [default to undefined]

## Example

```typescript
import { InputInvoiceMessageContent } from 'tele_rest';

const instance: InputInvoiceMessageContent = {
    title,
    description,
    payload,
    currency,
    prices,
    provider_token,
    max_tip_amount,
    suggested_tip_amounts,
    provider_data,
    photo_url,
    photo_size,
    photo_width,
    photo_height,
    need_name,
    need_phone_number,
    need_email,
    need_shipping_address,
    send_phone_number_to_provider,
    send_email_to_provider,
    is_flexible,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
