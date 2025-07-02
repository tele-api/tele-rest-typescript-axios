# RefundStarPaymentRequest

Request parameters for refundStarPayment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **number** | Identifier of the user whose payment will be refunded | [default to undefined]
**telegram_payment_charge_id** | **string** | Telegram payment identifier | [default to undefined]

## Example

```typescript
import { RefundStarPaymentRequest } from 'tele_rest';

const instance: RefundStarPaymentRequest = {
    user_id,
    telegram_payment_charge_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
