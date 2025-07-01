# InputMessageContent

This object represents the content of a message to be sent as a result of an inline query. Telegram clients currently support the following 5 types:  * [InputTextMessageContent](https://core.telegram.org/bots/api/#inputtextmessagecontent) * [InputLocationMessageContent](https://core.telegram.org/bots/api/#inputlocationmessagecontent) * [InputVenueMessageContent](https://core.telegram.org/bots/api/#inputvenuemessagecontent) * [InputContactMessageContent](https://core.telegram.org/bots/api/#inputcontactmessagecontent) * [InputInvoiceMessageContent](https://core.telegram.org/bots/api/#inputinvoicemessagecontent)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message_text** | **string** | Text of the message to be sent, 1-4096 characters | [default to undefined]
**latitude** | **number** | Latitude of the venue in degrees | [default to undefined]
**longitude** | **number** | Longitude of the venue in degrees | [default to undefined]
**title** | **string** | Product name, 1-32 characters | [default to undefined]
**address** | **string** | Address of the venue | [default to undefined]
**phone_number** | **string** | Contact\&#39;s phone number | [default to undefined]
**first_name** | **string** | Contact\&#39;s first name | [default to undefined]
**description** | **string** | Product description, 1-255 characters | [default to undefined]
**payload** | **string** | Bot-defined invoice payload, 1-128 bytes. This will not be displayed to the user, use it for your internal processes. | [default to undefined]
**currency** | **string** | Three-letter ISO 4217 currency code, see [more on currencies](https://core.telegram.org/bots/payments#supported-currencies). Pass “XTR” for payments in [Telegram Stars](https://t.me/BotNews/90). | [default to undefined]
**prices** | [**Array&lt;LabeledPrice&gt;**](LabeledPrice.md) | Price breakdown, a JSON-serialized list of components (e.g. product price, tax, discount, delivery cost, delivery tax, bonus, etc.). Must contain exactly one item for payments in [Telegram Stars](https://t.me/BotNews/90). | [default to undefined]
**parse_mode** | **string** | *Optional*. Mode for parsing entities in the message text. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. List of special entities that appear in message text, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**link_preview_options** | [**LinkPreviewOptions**](LinkPreviewOptions.md) |  | [optional] [default to undefined]
**horizontal_accuracy** | **number** | *Optional*. The radius of uncertainty for the location, measured in meters; 0-1500 | [optional] [default to undefined]
**live_period** | **number** | *Optional*. Period in seconds during which the location can be updated, should be between 60 and 86400, or 0x7FFFFFFF for live locations that can be edited indefinitely. | [optional] [default to undefined]
**heading** | **number** | *Optional*. For live locations, a direction in which the user is moving, in degrees. Must be between 1 and 360 if specified. | [optional] [default to undefined]
**proximity_alert_radius** | **number** | *Optional*. For live locations, a maximum distance for proximity alerts about approaching another chat member, in meters. Must be between 1 and 100000 if specified. | [optional] [default to undefined]
**foursquare_id** | **string** | *Optional*. Foursquare identifier of the venue, if known | [optional] [default to undefined]
**foursquare_type** | **string** | *Optional*. Foursquare type of the venue, if known. (For example, “arts\\_entertainment/default”, “arts\\_entertainment/aquarium” or “food/icecream”.) | [optional] [default to undefined]
**google_place_id** | **string** | *Optional*. Google Places identifier of the venue | [optional] [default to undefined]
**google_place_type** | **string** | *Optional*. Google Places type of the venue. (See [supported types](https://developers.google.com/places/web-service/supported_types).) | [optional] [default to undefined]
**last_name** | **string** | *Optional*. Contact\&#39;s last name | [optional] [default to undefined]
**vcard** | **string** | *Optional*. Additional data about the contact in the form of a [vCard](https://en.wikipedia.org/wiki/VCard), 0-2048 bytes | [optional] [default to undefined]
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
import { InputMessageContent } from 'tele_rest';

const instance: InputMessageContent = {
    message_text,
    latitude,
    longitude,
    title,
    address,
    phone_number,
    first_name,
    description,
    payload,
    currency,
    prices,
    parse_mode,
    entities,
    link_preview_options,
    horizontal_accuracy,
    live_period,
    heading,
    proximity_alert_radius,
    foursquare_id,
    foursquare_type,
    google_place_id,
    google_place_type,
    last_name,
    vcard,
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
