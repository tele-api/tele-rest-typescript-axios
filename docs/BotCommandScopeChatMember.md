# BotCommandScopeChatMember

Represents the [scope](https://core.telegram.org/bots/api/#botcommandscope) of bot commands, covering a specific member of a group or supergroup chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Scope type, must be *chat\\_member* | [default to 'chat_member']
**chat_id** | [**BotCommandScopeChatChatId**](BotCommandScopeChatChatId.md) |  | [default to undefined]
**user_id** | **number** | Unique identifier of the target user | [default to undefined]

## Example

```typescript
import { BotCommandScopeChatMember } from 'tele_rest';

const instance: BotCommandScopeChatMember = {
    type,
    chat_id,
    user_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
