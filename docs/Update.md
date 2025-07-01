# Update

This [object](https://core.telegram.org/bots/api/#available-types) represents an incoming update.   At most **one** of the optional parameters can be present in any given update.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**update_id** | **number** | The update\&#39;s unique identifier. Update identifiers start from a certain positive number and increase sequentially. This identifier becomes especially handy if you\&#39;re using [webhooks](https://core.telegram.org/bots/api/#setwebhook), since it allows you to ignore repeated updates or to restore the correct update sequence, should they get out of order. If there are no new updates for at least a week, then identifier of the next update will be chosen randomly instead of sequentially. | [default to undefined]
**message** | [**Message**](Message.md) |  | [optional] [default to undefined]
**edited_message** | [**Message**](Message.md) |  | [optional] [default to undefined]
**channel_post** | [**Message**](Message.md) |  | [optional] [default to undefined]
**edited_channel_post** | [**Message**](Message.md) |  | [optional] [default to undefined]
**business_connection** | [**BusinessConnection**](BusinessConnection.md) |  | [optional] [default to undefined]
**business_message** | [**Message**](Message.md) |  | [optional] [default to undefined]
**edited_business_message** | [**Message**](Message.md) |  | [optional] [default to undefined]
**deleted_business_messages** | [**BusinessMessagesDeleted**](BusinessMessagesDeleted.md) |  | [optional] [default to undefined]
**message_reaction** | [**MessageReactionUpdated**](MessageReactionUpdated.md) |  | [optional] [default to undefined]
**message_reaction_count** | [**MessageReactionCountUpdated**](MessageReactionCountUpdated.md) |  | [optional] [default to undefined]
**inline_query** | [**InlineQuery**](InlineQuery.md) |  | [optional] [default to undefined]
**chosen_inline_result** | [**ChosenInlineResult**](ChosenInlineResult.md) |  | [optional] [default to undefined]
**callback_query** | [**CallbackQuery**](CallbackQuery.md) |  | [optional] [default to undefined]
**shipping_query** | [**ShippingQuery**](ShippingQuery.md) |  | [optional] [default to undefined]
**pre_checkout_query** | [**PreCheckoutQuery**](PreCheckoutQuery.md) |  | [optional] [default to undefined]
**purchased_paid_media** | [**PaidMediaPurchased**](PaidMediaPurchased.md) |  | [optional] [default to undefined]
**poll** | [**Poll**](Poll.md) |  | [optional] [default to undefined]
**poll_answer** | [**PollAnswer**](PollAnswer.md) |  | [optional] [default to undefined]
**my_chat_member** | [**ChatMemberUpdated**](ChatMemberUpdated.md) |  | [optional] [default to undefined]
**chat_member** | [**ChatMemberUpdated**](ChatMemberUpdated.md) |  | [optional] [default to undefined]
**chat_join_request** | [**ChatJoinRequest**](ChatJoinRequest.md) |  | [optional] [default to undefined]
**chat_boost** | [**ChatBoostUpdated**](ChatBoostUpdated.md) |  | [optional] [default to undefined]
**removed_chat_boost** | [**ChatBoostRemoved**](ChatBoostRemoved.md) |  | [optional] [default to undefined]

## Example

```typescript
import { Update } from 'tele_rest';

const instance: Update = {
    update_id,
    message,
    edited_message,
    channel_post,
    edited_channel_post,
    business_connection,
    business_message,
    edited_business_message,
    deleted_business_messages,
    message_reaction,
    message_reaction_count,
    inline_query,
    chosen_inline_result,
    callback_query,
    shipping_query,
    pre_checkout_query,
    purchased_paid_media,
    poll,
    poll_answer,
    my_chat_member,
    chat_member,
    chat_join_request,
    chat_boost,
    removed_chat_boost,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
