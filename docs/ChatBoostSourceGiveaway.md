# ChatBoostSourceGiveaway

The boost was obtained by the creation of a Telegram Premium or a Telegram Star giveaway. This boosts the chat 4 times for the duration of the corresponding Telegram Premium subscription for Telegram Premium giveaways and *prize\\_star\\_count* / 500 times for one year for Telegram Star giveaways.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **string** | Source of the boost, always “giveaway” | [default to 'giveaway']
**giveaway_message_id** | **number** | Identifier of a message in the chat with the giveaway; the message could have been deleted already. May be 0 if the message isn\&#39;t sent yet. | [default to undefined]
**user** | [**User**](User.md) |  | [optional] [default to undefined]
**prize_star_count** | **number** | *Optional*. The number of Telegram Stars to be split between giveaway winners; for Telegram Star giveaways only | [optional] [default to undefined]
**is_unclaimed** | **boolean** | *Optional*. True, if the giveaway was completed, but there was no user to win the prize | [optional] [default to true]

## Example

```typescript
import { ChatBoostSourceGiveaway } from 'tele_rest';

const instance: ChatBoostSourceGiveaway = {
    source,
    giveaway_message_id,
    user,
    prize_star_count,
    is_unclaimed,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
