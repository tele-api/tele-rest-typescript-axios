# TransactionPartnerTelegramApi

Describes a transaction with payment for [paid broadcasting](https://core.telegram.org/bots/api/#paid-broadcasts).

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the transaction partner, always “telegram\\_api” | [default to 'telegram_api']
**request_count** | **number** | The number of successful requests that exceeded regular limits and were therefore billed | [default to undefined]

## Example

```typescript
import { TransactionPartnerTelegramApi } from 'tele_rest';

const instance: TransactionPartnerTelegramApi = {
    type,
    request_count,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
