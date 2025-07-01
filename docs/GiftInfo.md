# GiftInfo

Describes a service message about a regular gift that was sent or received.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gift** | [**Gift**](Gift.md) |  | [default to undefined]
**owned_gift_id** | **string** | *Optional*. Unique identifier of the received gift for the bot; only present for gifts received on behalf of business accounts | [optional] [default to undefined]
**convert_star_count** | **number** | *Optional*. Number of Telegram Stars that can be claimed by the receiver by converting the gift; omitted if conversion to Telegram Stars is impossible | [optional] [default to undefined]
**prepaid_upgrade_star_count** | **number** | *Optional*. Number of Telegram Stars that were prepaid by the sender for the ability to upgrade the gift | [optional] [default to undefined]
**can_be_upgraded** | **boolean** | *Optional*. True, if the gift can be upgraded to a unique gift | [optional] [default to true]
**text** | **string** | *Optional*. Text of the message that was added to the gift | [optional] [default to undefined]
**entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. Special entities that appear in the text | [optional] [default to undefined]
**is_private** | **boolean** | *Optional*. True, if the sender and gift text are shown only to the gift receiver; otherwise, everyone will be able to see them | [optional] [default to true]

## Example

```typescript
import { GiftInfo } from 'tele_rest';

const instance: GiftInfo = {
    gift,
    owned_gift_id,
    convert_star_count,
    prepaid_upgrade_star_count,
    can_be_upgraded,
    text,
    entities,
    is_private,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
