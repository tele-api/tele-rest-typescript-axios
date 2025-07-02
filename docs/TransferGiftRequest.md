# TransferGiftRequest

Request parameters for transferGift

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection | [default to undefined]
**owned_gift_id** | **string** | Unique identifier of the regular gift that should be transferred | [default to undefined]
**new_owner_chat_id** | **number** | Unique identifier of the chat which will own the gift. The chat must be active in the last 24 hours. | [default to undefined]
**star_count** | **number** | The amount of Telegram Stars that will be paid for the transfer from the business account balance. If positive, then the *can\\_transfer\\_stars* business bot right is required. | [optional] [default to undefined]

## Example

```typescript
import { TransferGiftRequest } from 'tele_rest';

const instance: TransferGiftRequest = {
    business_connection_id,
    owned_gift_id,
    new_owner_chat_id,
    star_count,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
