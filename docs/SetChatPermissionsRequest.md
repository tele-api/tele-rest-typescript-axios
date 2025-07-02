# SetChatPermissionsRequest

Request parameters for setChatPermissions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**BotCommandScopeChatChatId**](BotCommandScopeChatChatId.md) |  | [default to undefined]
**permissions** | [**ChatPermissions**](ChatPermissions.md) |  | [default to undefined]
**use_independent_chat_permissions** | **boolean** | Pass *True* if chat permissions are set independently. Otherwise, the *can\\_send\\_other\\_messages* and *can\\_add\\_web\\_page\\_previews* permissions will imply the *can\\_send\\_messages*, *can\\_send\\_audios*, *can\\_send\\_documents*, *can\\_send\\_photos*, *can\\_send\\_videos*, *can\\_send\\_video\\_notes*, and *can\\_send\\_voice\\_notes* permissions; the *can\\_send\\_polls* permission will imply the *can\\_send\\_messages* permission. | [optional] [default to undefined]

## Example

```typescript
import { SetChatPermissionsRequest } from 'tele_rest';

const instance: SetChatPermissionsRequest = {
    chat_id,
    permissions,
    use_independent_chat_permissions,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
