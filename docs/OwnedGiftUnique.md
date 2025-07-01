# OwnedGiftUnique

Describes a unique gift received and owned by a user or a chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the gift, always “unique” | [default to 'unique']
**gift** | [**UniqueGift**](UniqueGift.md) |  | [default to undefined]
**send_date** | **number** | Date the gift was sent in Unix time | [default to undefined]
**owned_gift_id** | **string** | *Optional*. Unique identifier of the received gift for the bot; for gifts received on behalf of business accounts only | [optional] [default to undefined]
**sender_user** | [**User**](User.md) |  | [optional] [default to undefined]
**is_saved** | **boolean** | *Optional*. True, if the gift is displayed on the account\&#39;s profile page; for gifts received on behalf of business accounts only | [optional] [default to true]
**can_be_transferred** | **boolean** | *Optional*. True, if the gift can be transferred to another owner; for gifts received on behalf of business accounts only | [optional] [default to true]
**transfer_star_count** | **number** | *Optional*. Number of Telegram Stars that must be paid to transfer the gift; omitted if the bot cannot transfer the gift | [optional] [default to undefined]

## Example

```typescript
import { OwnedGiftUnique } from 'tele_rest';

const instance: OwnedGiftUnique = {
    type,
    gift,
    send_date,
    owned_gift_id,
    sender_user,
    is_saved,
    can_be_transferred,
    transfer_star_count,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
