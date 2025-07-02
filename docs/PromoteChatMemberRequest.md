# PromoteChatMemberRequest

Request parameters for promoteChatMember

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessageRequestChatId**](SendMessageRequestChatId.md) |  | [default to undefined]
**user_id** | **number** | Unique identifier of the target user | [default to undefined]
**is_anonymous** | **boolean** | Pass *True* if the administrator\&#39;s presence in the chat is hidden | [optional] [default to undefined]
**can_manage_chat** | **boolean** | Pass *True* if the administrator can access the chat event log, get boost list, see hidden supergroup and channel members, report spam messages and ignore slow mode. Implied by any other administrator privilege. | [optional] [default to undefined]
**can_delete_messages** | **boolean** | Pass *True* if the administrator can delete messages of other users | [optional] [default to undefined]
**can_manage_video_chats** | **boolean** | Pass *True* if the administrator can manage video chats | [optional] [default to undefined]
**can_restrict_members** | **boolean** | Pass *True* if the administrator can restrict, ban or unban chat members, or access supergroup statistics | [optional] [default to undefined]
**can_promote_members** | **boolean** | Pass *True* if the administrator can add new administrators with a subset of their own privileges or demote administrators that they have promoted, directly or indirectly (promoted by administrators that were appointed by him) | [optional] [default to undefined]
**can_change_info** | **boolean** | Pass *True* if the administrator can change chat title, photo and other settings | [optional] [default to undefined]
**can_invite_users** | **boolean** | Pass *True* if the administrator can invite new users to the chat | [optional] [default to undefined]
**can_post_stories** | **boolean** | Pass *True* if the administrator can post stories to the chat | [optional] [default to undefined]
**can_edit_stories** | **boolean** | Pass *True* if the administrator can edit stories posted by other users, post stories to the chat page, pin chat stories, and access the chat\&#39;s story archive | [optional] [default to undefined]
**can_delete_stories** | **boolean** | Pass *True* if the administrator can delete stories posted by other users | [optional] [default to undefined]
**can_post_messages** | **boolean** | Pass *True* if the administrator can post messages in the channel, or access channel statistics; for channels only | [optional] [default to undefined]
**can_edit_messages** | **boolean** | Pass *True* if the administrator can edit messages of other users and can pin messages; for channels only | [optional] [default to undefined]
**can_pin_messages** | **boolean** | Pass *True* if the administrator can pin messages; for supergroups only | [optional] [default to undefined]
**can_manage_topics** | **boolean** | Pass *True* if the user is allowed to create, rename, close, and reopen forum topics; for supergroups only | [optional] [default to undefined]

## Example

```typescript
import { PromoteChatMemberRequest } from 'tele_rest';

const instance: PromoteChatMemberRequest = {
    chat_id,
    user_id,
    is_anonymous,
    can_manage_chat,
    can_delete_messages,
    can_manage_video_chats,
    can_restrict_members,
    can_promote_members,
    can_change_info,
    can_invite_users,
    can_post_stories,
    can_edit_stories,
    can_delete_stories,
    can_post_messages,
    can_edit_messages,
    can_pin_messages,
    can_manage_topics,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
