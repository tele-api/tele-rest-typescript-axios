# InlineQueryResultGame

Represents a [Game](https://core.telegram.org/bots/api/#games).

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *game* | [default to 'game']
**id** | **string** | Unique identifier for this result, 1-64 bytes | [default to undefined]
**game_short_name** | **string** | Short name of the game | [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultGame } from 'tele_rest';

const instance: InlineQueryResultGame = {
    type,
    id,
    game_short_name,
    reply_markup,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
