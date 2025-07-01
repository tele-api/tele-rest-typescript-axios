# Giveaway

This object represents a message about a scheduled giveaway.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chats** | [**Array&lt;Chat&gt;**](Chat.md) | The list of chats which the user must join to participate in the giveaway | [default to undefined]
**winners_selection_date** | **number** | Point in time (Unix timestamp) when winners of the giveaway will be selected | [default to undefined]
**winner_count** | **number** | The number of users which are supposed to be selected as winners of the giveaway | [default to undefined]
**only_new_members** | **boolean** | *Optional*. *True*, if only users who join the chats after the giveaway started should be eligible to win | [optional] [default to true]
**has_public_winners** | **boolean** | *Optional*. *True*, if the list of giveaway winners will be visible to everyone | [optional] [default to true]
**prize_description** | **string** | *Optional*. Description of additional giveaway prize | [optional] [default to undefined]
**country_codes** | **Array&lt;string&gt;** | *Optional*. A list of two-letter [ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) country codes indicating the countries from which eligible users for the giveaway must come. If empty, then all users can participate in the giveaway. Users with a phone number that was bought on Fragment can always participate in giveaways. | [optional] [default to undefined]
**prize_star_count** | **number** | *Optional*. The number of Telegram Stars to be split between giveaway winners; for Telegram Star giveaways only | [optional] [default to undefined]
**premium_subscription_month_count** | **number** | *Optional*. The number of months the Telegram Premium subscription won from the giveaway will be active for; for Telegram Premium giveaways only | [optional] [default to undefined]

## Example

```typescript
import { Giveaway } from 'tele_rest';

const instance: Giveaway = {
    chats,
    winners_selection_date,
    winner_count,
    only_new_members,
    has_public_winners,
    prize_description,
    country_codes,
    prize_star_count,
    premium_subscription_month_count,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
