# RevokeChatInviteLinkRequest

Request parameters for revokeChatInviteLink

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**RevokeChatInviteLinkRequestChatId**](RevokeChatInviteLinkRequestChatId.md) |  | [default to undefined]
**invite_link** | **string** | The invite link to revoke | [default to undefined]

## Example

```typescript
import { RevokeChatInviteLinkRequest } from 'tele_rest';

const instance: RevokeChatInviteLinkRequest = {
    chat_id,
    invite_link,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
