# EditChatSubscriptionInviteLinkRequest

Request parameters for editChatSubscriptionInviteLink

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessageRequestChatId**](SendMessageRequestChatId.md) |  | [default to undefined]
**invite_link** | **string** | The invite link to edit | [default to undefined]
**name** | **string** | Invite link name; 0-32 characters | [optional] [default to undefined]

## Example

```typescript
import { EditChatSubscriptionInviteLinkRequest } from 'tele_rest';

const instance: EditChatSubscriptionInviteLinkRequest = {
    chat_id,
    invite_link,
    name,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
