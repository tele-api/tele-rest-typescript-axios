# KeyboardButtonRequestChat

This object defines the criteria used to request a suitable chat. Information about the selected chat will be shared with the bot when the corresponding button is pressed. The bot will be granted requested rights in the chat if appropriate. [More about requesting chats »](https://core.telegram.org/bots/features#chat-and-user-selection).

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **number** | Signed 32-bit identifier of the request, which will be received back in the [ChatShared](https://core.telegram.org/bots/api/#chatshared) object. Must be unique within the message | [default to undefined]
**chat_is_channel** | **boolean** | Pass *True* to request a channel chat, pass *False* to request a group or a supergroup chat. | [default to undefined]
**chat_is_forum** | **boolean** | *Optional*. Pass *True* to request a forum supergroup, pass *False* to request a non-forum chat. If not specified, no additional restrictions are applied. | [optional] [default to undefined]
**chat_has_username** | **boolean** | *Optional*. Pass *True* to request a supergroup or a channel with a username, pass *False* to request a chat without a username. If not specified, no additional restrictions are applied. | [optional] [default to undefined]
**chat_is_created** | **boolean** | *Optional*. Pass *True* to request a chat owned by the user. Otherwise, no additional restrictions are applied. | [optional] [default to undefined]
**user_administrator_rights** | [**ChatAdministratorRights**](ChatAdministratorRights.md) |  | [optional] [default to undefined]
**bot_administrator_rights** | [**ChatAdministratorRights**](ChatAdministratorRights.md) |  | [optional] [default to undefined]
**bot_is_member** | **boolean** | *Optional*. Pass *True* to request a chat with the bot as a member. Otherwise, no additional restrictions are applied. | [optional] [default to undefined]
**request_title** | **boolean** | *Optional*. Pass *True* to request the chat\&#39;s title | [optional] [default to undefined]
**request_username** | **boolean** | *Optional*. Pass *True* to request the chat\&#39;s username | [optional] [default to undefined]
**request_photo** | **boolean** | *Optional*. Pass *True* to request the chat\&#39;s photo | [optional] [default to undefined]

## Example

```typescript
import { KeyboardButtonRequestChat } from 'tele_rest';

const instance: KeyboardButtonRequestChat = {
    request_id,
    chat_is_channel,
    chat_is_forum,
    chat_has_username,
    chat_is_created,
    user_administrator_rights,
    bot_administrator_rights,
    bot_is_member,
    request_title,
    request_username,
    request_photo,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
