# ReactionType

This object describes the type of a reaction. Currently, it can be one of  * [ReactionTypeEmoji](https://core.telegram.org/bots/api/#reactiontypeemoji) * [ReactionTypeCustomEmoji](https://core.telegram.org/bots/api/#reactiontypecustomemoji) * [ReactionTypePaid](https://core.telegram.org/bots/api/#reactiontypepaid)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the reaction, always “paid” | [default to 'paid']
**emoji** | **string** | Reaction emoji. Currently, it can be one of \&quot;❤\&quot;, \&quot;👍\&quot;, \&quot;👎\&quot;, \&quot;🔥\&quot;, \&quot;🥰\&quot;, \&quot;👏\&quot;, \&quot;😁\&quot;, \&quot;🤔\&quot;, \&quot;🤯\&quot;, \&quot;😱\&quot;, \&quot;🤬\&quot;, \&quot;😢\&quot;, \&quot;🎉\&quot;, \&quot;🤩\&quot;, \&quot;🤮\&quot;, \&quot;💩\&quot;, \&quot;🙏\&quot;, \&quot;👌\&quot;, \&quot;🕊\&quot;, \&quot;🤡\&quot;, \&quot;🥱\&quot;, \&quot;🥴\&quot;, \&quot;😍\&quot;, \&quot;🐳\&quot;, \&quot;❤‍🔥\&quot;, \&quot;🌚\&quot;, \&quot;🌭\&quot;, \&quot;💯\&quot;, \&quot;🤣\&quot;, \&quot;⚡\&quot;, \&quot;🍌\&quot;, \&quot;🏆\&quot;, \&quot;💔\&quot;, \&quot;🤨\&quot;, \&quot;😐\&quot;, \&quot;🍓\&quot;, \&quot;🍾\&quot;, \&quot;💋\&quot;, \&quot;🖕\&quot;, \&quot;😈\&quot;, \&quot;😴\&quot;, \&quot;😭\&quot;, \&quot;🤓\&quot;, \&quot;👻\&quot;, \&quot;👨‍💻\&quot;, \&quot;👀\&quot;, \&quot;🎃\&quot;, \&quot;🙈\&quot;, \&quot;😇\&quot;, \&quot;😨\&quot;, \&quot;🤝\&quot;, \&quot;✍\&quot;, \&quot;🤗\&quot;, \&quot;🫡\&quot;, \&quot;🎅\&quot;, \&quot;🎄\&quot;, \&quot;☃\&quot;, \&quot;💅\&quot;, \&quot;🤪\&quot;, \&quot;🗿\&quot;, \&quot;🆒\&quot;, \&quot;💘\&quot;, \&quot;🙉\&quot;, \&quot;🦄\&quot;, \&quot;😘\&quot;, \&quot;💊\&quot;, \&quot;🙊\&quot;, \&quot;😎\&quot;, \&quot;👾\&quot;, \&quot;🤷‍♂\&quot;, \&quot;🤷\&quot;, \&quot;🤷‍♀\&quot;, \&quot;😡\&quot; | [default to undefined]
**custom_emoji_id** | **string** | Custom emoji identifier | [default to undefined]

## Example

```typescript
import { ReactionType } from 'tele_rest';

const instance: ReactionType = {
    type,
    emoji,
    custom_emoji_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
