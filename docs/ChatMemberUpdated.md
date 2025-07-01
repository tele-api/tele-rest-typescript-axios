# ChatMemberUpdated

This object represents changes in the status of a chat member.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat** | [**Chat**](Chat.md) |  | [default to undefined]
**from** | [**User**](User.md) |  | [default to undefined]
**date** | **number** | Date the change was done in Unix time | [default to undefined]
**old_chat_member** | [**ChatMember**](ChatMember.md) |  | [default to undefined]
**new_chat_member** | [**ChatMember**](ChatMember.md) |  | [default to undefined]
**invite_link** | [**ChatInviteLink**](ChatInviteLink.md) |  | [optional] [default to undefined]
**via_join_request** | **boolean** | *Optional*. True, if the user joined the chat after sending a direct join request without using an invite link and being approved by an administrator | [optional] [default to undefined]
**via_chat_folder_invite_link** | **boolean** | *Optional*. True, if the user joined the chat via a chat folder invite link | [optional] [default to undefined]

## Example

```typescript
import { ChatMemberUpdated } from 'tele_rest';

const instance: ChatMemberUpdated = {
    chat,
    from,
    date,
    old_chat_member,
    new_chat_member,
    invite_link,
    via_join_request,
    via_chat_folder_invite_link,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
