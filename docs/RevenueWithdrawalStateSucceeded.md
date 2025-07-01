# RevenueWithdrawalStateSucceeded

The withdrawal succeeded.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the state, always “succeeded” | [default to 'succeeded']
**date** | **number** | Date the withdrawal was completed in Unix time | [default to undefined]
**url** | **string** | An HTTPS URL that can be used to see transaction details | [default to undefined]

## Example

```typescript
import { RevenueWithdrawalStateSucceeded } from 'tele_rest';

const instance: RevenueWithdrawalStateSucceeded = {
    type,
    date,
    url,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
