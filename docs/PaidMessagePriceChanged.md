# PaidMessagePriceChanged

Describes a service message about a change in the price of paid messages within a chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**paid_message_star_count** | **number** | The new number of Telegram Stars that must be paid by non-administrator users of the supergroup chat for each sent message | [default to undefined]

## Example

```typescript
import { PaidMessagePriceChanged } from 'tele_rest';

const instance: PaidMessagePriceChanged = {
    paid_message_star_count,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
