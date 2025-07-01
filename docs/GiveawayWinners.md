# GiveawayWinners

This object represents a message about the completion of a giveaway with public winners.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat** | [**Chat**](Chat.md) |  | [default to undefined]
**giveaway_message_id** | **number** | Identifier of the message with the giveaway in the chat | [default to undefined]
**winners_selection_date** | **number** | Point in time (Unix timestamp) when winners of the giveaway were selected | [default to undefined]
**winner_count** | **number** | Total number of winners in the giveaway | [default to undefined]
**winners** | [**Array&lt;User&gt;**](User.md) | List of up to 100 winners of the giveaway | [default to undefined]
**additional_chat_count** | **number** | *Optional*. The number of other chats the user had to join in order to be eligible for the giveaway | [optional] [default to undefined]
**prize_star_count** | **number** | *Optional*. The number of Telegram Stars that were split between giveaway winners; for Telegram Star giveaways only | [optional] [default to undefined]
**premium_subscription_month_count** | **number** | *Optional*. The number of months the Telegram Premium subscription won from the giveaway will be active for; for Telegram Premium giveaways only | [optional] [default to undefined]
**unclaimed_prize_count** | **number** | *Optional*. Number of undistributed prizes | [optional] [default to undefined]
**only_new_members** | **boolean** | *Optional*. *True*, if only users who had joined the chats after the giveaway started were eligible to win | [optional] [default to true]
**was_refunded** | **boolean** | *Optional*. *True*, if the giveaway was canceled because the payment for it was refunded | [optional] [default to true]
**prize_description** | **string** | *Optional*. Description of additional giveaway prize | [optional] [default to undefined]

## Example

```typescript
import { GiveawayWinners } from 'tele_rest';

const instance: GiveawayWinners = {
    chat,
    giveaway_message_id,
    winners_selection_date,
    winner_count,
    winners,
    additional_chat_count,
    prize_star_count,
    premium_subscription_month_count,
    unclaimed_prize_count,
    only_new_members,
    was_refunded,
    prize_description,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
