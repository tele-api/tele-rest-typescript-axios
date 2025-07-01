# CallbackQuery

This object represents an incoming callback query from a callback button in an [inline keyboard](https://core.telegram.org/bots/features#inline-keyboards). If the button that originated the query was attached to a message sent by the bot, the field *message* will be present. If the button was attached to a message sent via the bot (in [inline mode](https://core.telegram.org/bots/api/#inline-mode)), the field *inline\\_message\\_id* will be present. Exactly one of the fields *data* or *game\\_short\\_name* will be present.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this query | [default to undefined]
**from** | [**User**](User.md) |  | [default to undefined]
**chat_instance** | **string** | Global identifier, uniquely corresponding to the chat to which the message with the callback button was sent. Useful for high scores in [games](https://core.telegram.org/bots/api/#games). | [default to undefined]
**message** | [**MaybeInaccessibleMessage**](MaybeInaccessibleMessage.md) |  | [optional] [default to undefined]
**inline_message_id** | **string** | *Optional*. Identifier of the message sent via the bot in inline mode, that originated the query. | [optional] [default to undefined]
**data** | **string** | *Optional*. Data associated with the callback button. Be aware that the message originated the query can contain no callback buttons with this data. | [optional] [default to undefined]
**game_short_name** | **string** | *Optional*. Short name of a [Game](https://core.telegram.org/bots/api/#games) to be returned, serves as the unique identifier for the game | [optional] [default to undefined]

## Example

```typescript
import { CallbackQuery } from 'tele_rest';

const instance: CallbackQuery = {
    id,
    from,
    chat_instance,
    message,
    inline_message_id,
    data,
    game_short_name,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
