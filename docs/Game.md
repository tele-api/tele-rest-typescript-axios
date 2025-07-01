# Game

This object represents a game. Use BotFather to create and edit games, their short names will act as unique identifiers.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **string** | Title of the game | [default to undefined]
**description** | **string** | Description of the game | [default to undefined]
**photo** | [**Array&lt;PhotoSize&gt;**](PhotoSize.md) | Photo that will be displayed in the game message in chats. | [default to undefined]
**text** | **string** | *Optional*. Brief description of the game or high scores included in the game message. Can be automatically edited to include current high scores for the game when the bot calls [setGameScore](https://core.telegram.org/bots/api/#setgamescore), or manually edited using [editMessageText](https://core.telegram.org/bots/api/#editmessagetext). 0-4096 characters. | [optional] [default to undefined]
**text_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. Special entities that appear in *text*, such as usernames, URLs, bot commands, etc. | [optional] [default to undefined]
**animation** | [**Animation**](Animation.md) |  | [optional] [default to undefined]

## Example

```typescript
import { Game } from 'tele_rest';

const instance: Game = {
    title,
    description,
    photo,
    text,
    text_entities,
    animation,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
