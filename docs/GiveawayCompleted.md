# GiveawayCompleted

This object represents a service message about the completion of a giveaway without public winners.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**winner_count** | **number** | Number of winners in the giveaway | [default to undefined]
**unclaimed_prize_count** | **number** | *Optional*. Number of undistributed prizes | [optional] [default to undefined]
**giveaway_message** | [**Message**](Message.md) |  | [optional] [default to undefined]
**is_star_giveaway** | **boolean** | *Optional*. *True*, if the giveaway is a Telegram Star giveaway. Otherwise, currently, the giveaway is a Telegram Premium giveaway. | [optional] [default to true]

## Example

```typescript
import { GiveawayCompleted } from 'tele_rest';

const instance: GiveawayCompleted = {
    winner_count,
    unclaimed_prize_count,
    giveaway_message,
    is_star_giveaway,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
