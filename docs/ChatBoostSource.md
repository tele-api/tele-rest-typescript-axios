# ChatBoostSource

This object describes the source of a chat boost. It can be one of  * [ChatBoostSourcePremium](https://core.telegram.org/bots/api/#chatboostsourcepremium) * [ChatBoostSourceGiftCode](https://core.telegram.org/bots/api/#chatboostsourcegiftcode) * [ChatBoostSourceGiveaway](https://core.telegram.org/bots/api/#chatboostsourcegiveaway)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **string** | Source of the boost, always “giveaway” | [default to 'giveaway']
**user** | [**User**](User.md) |  | [default to undefined]
**giveaway_message_id** | **number** | Identifier of a message in the chat with the giveaway; the message could have been deleted already. May be 0 if the message isn\&#39;t sent yet. | [default to undefined]
**prize_star_count** | **number** | *Optional*. The number of Telegram Stars to be split between giveaway winners; for Telegram Star giveaways only | [optional] [default to undefined]
**is_unclaimed** | **boolean** | *Optional*. True, if the giveaway was completed, but there was no user to win the prize | [optional] [default to true]

## Example

```typescript
import { ChatBoostSource } from 'tele_rest';

const instance: ChatBoostSource = {
    source,
    user,
    giveaway_message_id,
    prize_star_count,
    is_unclaimed,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
