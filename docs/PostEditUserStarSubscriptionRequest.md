# PostEditUserStarSubscriptionRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **number** | Identifier of the user whose subscription will be edited | [default to undefined]
**telegram_payment_charge_id** | **string** | Telegram payment identifier for the subscription | [default to undefined]
**is_canceled** | **boolean** | Pass *True* to cancel extension of the user subscription; the subscription must be active up to the end of the current subscription period. Pass *False* to allow the user to re-enable a subscription that was previously canceled by the bot. | [default to undefined]

## Example

```typescript
import { PostEditUserStarSubscriptionRequest } from 'tele_rest';

const instance: PostEditUserStarSubscriptionRequest = {
    user_id,
    telegram_payment_charge_id,
    is_canceled,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
