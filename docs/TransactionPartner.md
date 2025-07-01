# TransactionPartner

This object describes the source of a transaction, or its recipient for outgoing transactions. Currently, it can be one of  * [TransactionPartnerUser](https://core.telegram.org/bots/api/#transactionpartneruser) * [TransactionPartnerChat](https://core.telegram.org/bots/api/#transactionpartnerchat) * [TransactionPartnerAffiliateProgram](https://core.telegram.org/bots/api/#transactionpartneraffiliateprogram) * [TransactionPartnerFragment](https://core.telegram.org/bots/api/#transactionpartnerfragment) * [TransactionPartnerTelegramAds](https://core.telegram.org/bots/api/#transactionpartnertelegramads) * [TransactionPartnerTelegramApi](https://core.telegram.org/bots/api/#transactionpartnertelegramapi) * [TransactionPartnerOther](https://core.telegram.org/bots/api/#transactionpartnerother)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the transaction partner, always “other” | [default to 'other']
**transaction_type** | **string** | Type of the transaction, currently one of “invoice\\_payment” for payments via invoices, “paid\\_media\\_payment” for payments for paid media, “gift\\_purchase” for gifts sent by the bot, “premium\\_purchase” for Telegram Premium subscriptions gifted by the bot, “business\\_account\\_transfer” for direct transfers from managed business accounts | [default to undefined]
**user** | [**User**](User.md) |  | [default to undefined]
**chat** | [**Chat**](Chat.md) |  | [default to undefined]
**commission_per_mille** | **number** | The number of Telegram Stars received by the bot for each 1000 Telegram Stars received by the affiliate program sponsor from referred users | [default to undefined]
**request_count** | **number** | The number of successful requests that exceeded regular limits and were therefore billed | [default to undefined]
**affiliate** | [**AffiliateInfo**](AffiliateInfo.md) |  | [optional] [default to undefined]
**invoice_payload** | **string** | *Optional*. Bot-specified invoice payload. Can be available only for “invoice\\_payment” transactions. | [optional] [default to undefined]
**subscription_period** | **number** | *Optional*. The duration of the paid subscription. Can be available only for “invoice\\_payment” transactions. | [optional] [default to undefined]
**paid_media** | [**Array&lt;PaidMedia&gt;**](PaidMedia.md) | *Optional*. Information about the paid media bought by the user; for “paid\\_media\\_payment” transactions only | [optional] [default to undefined]
**paid_media_payload** | **string** | *Optional*. Bot-specified paid media payload. Can be available only for “paid\\_media\\_payment” transactions. | [optional] [default to undefined]
**gift** | [**Gift**](Gift.md) |  | [optional] [default to undefined]
**premium_subscription_duration** | **number** | *Optional*. Number of months the gifted Telegram Premium subscription will be active for; for “premium\\_purchase” transactions only | [optional] [default to undefined]
**sponsor_user** | [**User**](User.md) |  | [optional] [default to undefined]
**withdrawal_state** | [**RevenueWithdrawalState**](RevenueWithdrawalState.md) |  | [optional] [default to undefined]

## Example

```typescript
import { TransactionPartner } from 'tele_rest';

const instance: TransactionPartner = {
    type,
    transaction_type,
    user,
    chat,
    commission_per_mille,
    request_count,
    affiliate,
    invoice_payload,
    subscription_period,
    paid_media,
    paid_media_payload,
    gift,
    premium_subscription_duration,
    sponsor_user,
    withdrawal_state,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
