# Gift

This object represents a gift that can be sent by the bot.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier of the gift | [default to undefined]
**sticker** | [**Sticker**](Sticker.md) |  | [default to undefined]
**star_count** | **number** | The number of Telegram Stars that must be paid to send the sticker | [default to undefined]
**upgrade_star_count** | **number** | *Optional*. The number of Telegram Stars that must be paid to upgrade the gift to a unique one | [optional] [default to undefined]
**total_count** | **number** | *Optional*. The total number of the gifts of this type that can be sent; for limited gifts only | [optional] [default to undefined]
**remaining_count** | **number** | *Optional*. The number of remaining gifts of this type that can be sent; for limited gifts only | [optional] [default to undefined]

## Example

```typescript
import { Gift } from 'tele_rest';

const instance: Gift = {
    id,
    sticker,
    star_count,
    upgrade_star_count,
    total_count,
    remaining_count,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
