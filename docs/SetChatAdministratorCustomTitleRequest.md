# SetChatAdministratorCustomTitleRequest

Request parameters for setChatAdministratorCustomTitle

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**BotCommandScopeChatChatId**](BotCommandScopeChatChatId.md) |  | [default to undefined]
**user_id** | **number** | Unique identifier of the target user | [default to undefined]
**custom_title** | **string** | New custom title for the administrator; 0-16 characters, emoji are not allowed | [default to undefined]

## Example

```typescript
import { SetChatAdministratorCustomTitleRequest } from 'tele_rest';

const instance: SetChatAdministratorCustomTitleRequest = {
    chat_id,
    user_id,
    custom_title,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
