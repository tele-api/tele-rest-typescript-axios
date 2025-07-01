# TransactionPartnerFragment

Describes a withdrawal transaction with Fragment.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the transaction partner, always “fragment” | [default to 'fragment']
**withdrawal_state** | [**RevenueWithdrawalState**](RevenueWithdrawalState.md) |  | [optional] [default to undefined]

## Example

```typescript
import { TransactionPartnerFragment } from 'tele_rest';

const instance: TransactionPartnerFragment = {
    type,
    withdrawal_state,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
