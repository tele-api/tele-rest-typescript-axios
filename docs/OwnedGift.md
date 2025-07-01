# OwnedGift

This object describes a gift received and owned by a user or a chat. Currently, it can be one of  * [OwnedGiftRegular](https://core.telegram.org/bots/api/#ownedgiftregular) * [OwnedGiftUnique](https://core.telegram.org/bots/api/#ownedgiftunique)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the gift, always “unique” | [default to 'unique']
**gift** | [**UniqueGift**](UniqueGift.md) |  | [default to undefined]
**send_date** | **number** | Date the gift was sent in Unix time | [default to undefined]
**owned_gift_id** | **string** | *Optional*. Unique identifier of the received gift for the bot; for gifts received on behalf of business accounts only | [optional] [default to undefined]
**sender_user** | [**User**](User.md) |  | [optional] [default to undefined]
**text** | **string** | *Optional*. Text of the message that was added to the gift | [optional] [default to undefined]
**entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. Special entities that appear in the text | [optional] [default to undefined]
**is_private** | **boolean** | *Optional*. True, if the sender and gift text are shown only to the gift receiver; otherwise, everyone will be able to see them | [optional] [default to true]
**is_saved** | **boolean** | *Optional*. True, if the gift is displayed on the account\&#39;s profile page; for gifts received on behalf of business accounts only | [optional] [default to true]
**can_be_upgraded** | **boolean** | *Optional*. True, if the gift can be upgraded to a unique gift; for gifts received on behalf of business accounts only | [optional] [default to true]
**was_refunded** | **boolean** | *Optional*. True, if the gift was refunded and isn\&#39;t available anymore | [optional] [default to true]
**convert_star_count** | **number** | *Optional*. Number of Telegram Stars that can be claimed by the receiver instead of the gift; omitted if the gift cannot be converted to Telegram Stars | [optional] [default to undefined]
**prepaid_upgrade_star_count** | **number** | *Optional*. Number of Telegram Stars that were paid by the sender for the ability to upgrade the gift | [optional] [default to undefined]
**can_be_transferred** | **boolean** | *Optional*. True, if the gift can be transferred to another owner; for gifts received on behalf of business accounts only | [optional] [default to true]
**transfer_star_count** | **number** | *Optional*. Number of Telegram Stars that must be paid to transfer the gift; omitted if the bot cannot transfer the gift | [optional] [default to undefined]

## Example

```typescript
import { OwnedGift } from 'tele_rest';

const instance: OwnedGift = {
    type,
    gift,
    send_date,
    owned_gift_id,
    sender_user,
    text,
    entities,
    is_private,
    is_saved,
    can_be_upgraded,
    was_refunded,
    convert_star_count,
    prepaid_upgrade_star_count,
    can_be_transferred,
    transfer_star_count,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
