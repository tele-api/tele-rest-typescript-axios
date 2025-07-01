# TransactionPartnerUser

Describes a transaction with a user.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the transaction partner, always “user” | [default to 'user']
**transaction_type** | **string** | Type of the transaction, currently one of “invoice\\_payment” for payments via invoices, “paid\\_media\\_payment” for payments for paid media, “gift\\_purchase” for gifts sent by the bot, “premium\\_purchase” for Telegram Premium subscriptions gifted by the bot, “business\\_account\\_transfer” for direct transfers from managed business accounts | [default to undefined]
**user** | [**User**](User.md) |  | [default to undefined]
**affiliate** | [**AffiliateInfo**](AffiliateInfo.md) |  | [optional] [default to undefined]
**invoice_payload** | **string** | *Optional*. Bot-specified invoice payload. Can be available only for “invoice\\_payment” transactions. | [optional] [default to undefined]
**subscription_period** | **number** | *Optional*. The duration of the paid subscription. Can be available only for “invoice\\_payment” transactions. | [optional] [default to undefined]
**paid_media** | [**Array&lt;PaidMedia&gt;**](PaidMedia.md) | *Optional*. Information about the paid media bought by the user; for “paid\\_media\\_payment” transactions only | [optional] [default to undefined]
**paid_media_payload** | **string** | *Optional*. Bot-specified paid media payload. Can be available only for “paid\\_media\\_payment” transactions. | [optional] [default to undefined]
**gift** | [**Gift**](Gift.md) |  | [optional] [default to undefined]
**premium_subscription_duration** | **number** | *Optional*. Number of months the gifted Telegram Premium subscription will be active for; for “premium\\_purchase” transactions only | [optional] [default to undefined]

## Example

```typescript
import { TransactionPartnerUser } from 'tele_rest';

const instance: TransactionPartnerUser = {
    type,
    transaction_type,
    user,
    affiliate,
    invoice_payload,
    subscription_period,
    paid_media,
    paid_media_payload,
    gift,
    premium_subscription_duration,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
