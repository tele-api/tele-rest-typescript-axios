# BotCommandScopeChatAdministrators

Represents the [scope](https://core.telegram.org/bots/api/#botcommandscope) of bot commands, covering all administrators of a specific group or supergroup chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Scope type, must be *chat\\_administrators* | [default to 'chat_administrators']
**chat_id** | [**RestrictChatMemberPostRequestChatId**](RestrictChatMemberPostRequestChatId.md) |  | [default to undefined]

## Example

```typescript
import { BotCommandScopeChatAdministrators } from 'tele_rest';

const instance: BotCommandScopeChatAdministrators = {
    type,
    chat_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
