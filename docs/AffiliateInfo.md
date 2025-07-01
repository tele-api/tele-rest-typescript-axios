# AffiliateInfo

Contains information about the affiliate that received a commission via this transaction.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**commission_per_mille** | **number** | The number of Telegram Stars received by the affiliate for each 1000 Telegram Stars received by the bot from referred users | [default to undefined]
**amount** | **number** | Integer amount of Telegram Stars received by the affiliate from the transaction, rounded to 0; can be negative for refunds | [default to undefined]
**affiliate_user** | [**User**](User.md) |  | [optional] [default to undefined]
**affiliate_chat** | [**Chat**](Chat.md) |  | [optional] [default to undefined]
**nanostar_amount** | **number** | *Optional*. The number of 1/1000000000 shares of Telegram Stars received by the affiliate; from -999999999 to 999999999; can be negative for refunds | [optional] [default to undefined]

## Example

```typescript
import { AffiliateInfo } from 'tele_rest';

const instance: AffiliateInfo = {
    commission_per_mille,
    amount,
    affiliate_user,
    affiliate_chat,
    nanostar_amount,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
