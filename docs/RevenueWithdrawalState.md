# RevenueWithdrawalState

This object describes the state of a revenue withdrawal operation. Currently, it can be one of  * [RevenueWithdrawalStatePending](https://core.telegram.org/bots/api/#revenuewithdrawalstatepending) * [RevenueWithdrawalStateSucceeded](https://core.telegram.org/bots/api/#revenuewithdrawalstatesucceeded) * [RevenueWithdrawalStateFailed](https://core.telegram.org/bots/api/#revenuewithdrawalstatefailed)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the state, always “failed” | [default to 'failed']
**date** | **number** | Date the withdrawal was completed in Unix time | [default to undefined]
**url** | **string** | An HTTPS URL that can be used to see transaction details | [default to undefined]

## Example

```typescript
import { RevenueWithdrawalState } from 'tele_rest';

const instance: RevenueWithdrawalState = {
    type,
    date,
    url,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
