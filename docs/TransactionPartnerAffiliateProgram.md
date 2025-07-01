# TransactionPartnerAffiliateProgram

Describes the affiliate program that issued the affiliate commission received via this transaction.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the transaction partner, always “affiliate\\_program” | [default to 'affiliate_program']
**commission_per_mille** | **number** | The number of Telegram Stars received by the bot for each 1000 Telegram Stars received by the affiliate program sponsor from referred users | [default to undefined]
**sponsor_user** | [**User**](User.md) |  | [optional] [default to undefined]

## Example

```typescript
import { TransactionPartnerAffiliateProgram } from 'tele_rest';

const instance: TransactionPartnerAffiliateProgram = {
    type,
    commission_per_mille,
    sponsor_user,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
