# OwnedGiftRegular

Describes a regular gift owned by a user or a chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the gift, always “regular” | [default to 'regular']
**gift** | [**Gift**](Gift.md) |  | [default to undefined]
**send_date** | **number** | Date the gift was sent in Unix time | [default to undefined]
**owned_gift_id** | **string** | *Optional*. Unique identifier of the gift for the bot; for gifts received on behalf of business accounts only | [optional] [default to undefined]
**sender_user** | [**User**](User.md) |  | [optional] [default to undefined]
**text** | **string** | *Optional*. Text of the message that was added to the gift | [optional] [default to undefined]
**entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. Special entities that appear in the text | [optional] [default to undefined]
**is_private** | **boolean** | *Optional*. True, if the sender and gift text are shown only to the gift receiver; otherwise, everyone will be able to see them | [optional] [default to true]
**is_saved** | **boolean** | *Optional*. True, if the gift is displayed on the account\&#39;s profile page; for gifts received on behalf of business accounts only | [optional] [default to true]
**can_be_upgraded** | **boolean** | *Optional*. True, if the gift can be upgraded to a unique gift; for gifts received on behalf of business accounts only | [optional] [default to true]
**was_refunded** | **boolean** | *Optional*. True, if the gift was refunded and isn\&#39;t available anymore | [optional] [default to true]
**convert_star_count** | **number** | *Optional*. Number of Telegram Stars that can be claimed by the receiver instead of the gift; omitted if the gift cannot be converted to Telegram Stars | [optional] [default to undefined]
**prepaid_upgrade_star_count** | **number** | *Optional*. Number of Telegram Stars that were paid by the sender for the ability to upgrade the gift | [optional] [default to undefined]

## Example

```typescript
import { OwnedGiftRegular } from 'tele_rest';

const instance: OwnedGiftRegular = {
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
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
