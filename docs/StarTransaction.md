# StarTransaction

Describes a Telegram Star transaction. Note that if the buyer initiates a chargeback with the payment provider from whom they acquired Stars (e.g., Apple, Google) following this transaction, the refunded Stars will be deducted from the bot\'s balance. This is outside of Telegram\'s control.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier of the transaction. Coincides with the identifier of the original transaction for refund transactions. Coincides with *SuccessfulPayment.telegram\\_payment\\_charge\\_id* for successful incoming payments from users. | [default to undefined]
**amount** | **number** | Integer amount of Telegram Stars transferred by the transaction | [default to undefined]
**date** | **number** | Date the transaction was created in Unix time | [default to undefined]
**nanostar_amount** | **number** | *Optional*. The number of 1/1000000000 shares of Telegram Stars transferred by the transaction; from 0 to 999999999 | [optional] [default to undefined]
**source** | [**TransactionPartner**](TransactionPartner.md) |  | [optional] [default to undefined]
**receiver** | [**TransactionPartner**](TransactionPartner.md) |  | [optional] [default to undefined]

## Example

```typescript
import { StarTransaction } from 'tele_rest';

const instance: StarTransaction = {
    id,
    amount,
    date,
    nanostar_amount,
    source,
    receiver,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
