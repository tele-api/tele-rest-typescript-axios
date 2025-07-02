# PostEditChatInviteLinkRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**PostSendMessageRequestChatId**](PostSendMessageRequestChatId.md) |  | [default to undefined]
**invite_link** | **string** | The invite link to edit | [default to undefined]
**name** | **string** | Invite link name; 0-32 characters | [optional] [default to undefined]
**expire_date** | **number** | Point in time (Unix timestamp) when the link will expire | [optional] [default to undefined]
**member_limit** | **number** | The maximum number of users that can be members of the chat simultaneously after joining the chat via this invite link; 1-99999 | [optional] [default to undefined]
**creates_join_request** | **boolean** | *True*, if users joining the chat via the link need to be approved by chat administrators. If *True*, *member\\_limit* can\&#39;t be specified | [optional] [default to undefined]

## Example

```typescript
import { PostEditChatInviteLinkRequest } from 'tele_rest';

const instance: PostEditChatInviteLinkRequest = {
    chat_id,
    invite_link,
    name,
    expire_date,
    member_limit,
    creates_join_request,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
