# UniqueGiftInfo

Describes a service message about a unique gift that was sent or received.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gift** | [**UniqueGift**](UniqueGift.md) |  | [default to undefined]
**origin** | **string** | Origin of the gift. Currently, either “upgrade” or “transfer” | [default to undefined]
**owned_gift_id** | **string** | *Optional*. Unique identifier of the received gift for the bot; only present for gifts received on behalf of business accounts | [optional] [default to undefined]
**transfer_star_count** | **number** | *Optional*. Number of Telegram Stars that must be paid to transfer the gift; omitted if the bot cannot transfer the gift | [optional] [default to undefined]

## Example

```typescript
import { UniqueGiftInfo } from 'tele_rest';

const instance: UniqueGiftInfo = {
    gift,
    origin,
    owned_gift_id,
    transfer_star_count,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
