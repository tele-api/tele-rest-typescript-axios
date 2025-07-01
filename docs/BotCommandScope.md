# BotCommandScope

This object represents the scope to which bot commands are applied. Currently, the following 7 scopes are supported:  * [BotCommandScopeDefault](https://core.telegram.org/bots/api/#botcommandscopedefault) * [BotCommandScopeAllPrivateChats](https://core.telegram.org/bots/api/#botcommandscopeallprivatechats) * [BotCommandScopeAllGroupChats](https://core.telegram.org/bots/api/#botcommandscopeallgroupchats) * [BotCommandScopeAllChatAdministrators](https://core.telegram.org/bots/api/#botcommandscopeallchatadministrators) * [BotCommandScopeChat](https://core.telegram.org/bots/api/#botcommandscopechat) * [BotCommandScopeChatAdministrators](https://core.telegram.org/bots/api/#botcommandscopechatadministrators) * [BotCommandScopeChatMember](https://core.telegram.org/bots/api/#botcommandscopechatmember)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Scope type, must be *chat\\_member* | [default to 'chat_member']
**chat_id** | [**RestrictChatMemberPostRequestChatId**](RestrictChatMemberPostRequestChatId.md) |  | [default to undefined]
**user_id** | **number** | Unique identifier of the target user | [default to undefined]

## Example

```typescript
import { BotCommandScope } from 'tele_rest';

const instance: BotCommandScope = {
    type,
    chat_id,
    user_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
