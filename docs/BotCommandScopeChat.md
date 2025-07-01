# BotCommandScopeChat

Represents the [scope](https://core.telegram.org/bots/api/#botcommandscope) of bot commands, covering a specific chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Scope type, must be *chat* | [default to 'chat']
**chat_id** | [**RestrictChatMemberPostRequestChatId**](RestrictChatMemberPostRequestChatId.md) |  | [default to undefined]

## Example

```typescript
import { BotCommandScopeChat } from 'tele_rest';

const instance: BotCommandScopeChat = {
    type,
    chat_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
