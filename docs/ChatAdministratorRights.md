# ChatAdministratorRights

Represents the rights of an administrator in a chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**is_anonymous** | **boolean** | *True*, if the user\&#39;s presence in the chat is hidden | [default to undefined]
**can_manage_chat** | **boolean** | *True*, if the administrator can access the chat event log, get boost list, see hidden supergroup and channel members, report spam messages and ignore slow mode. Implied by any other administrator privilege. | [default to undefined]
**can_delete_messages** | **boolean** | *True*, if the administrator can delete messages of other users | [default to undefined]
**can_manage_video_chats** | **boolean** | *True*, if the administrator can manage video chats | [default to undefined]
**can_restrict_members** | **boolean** | *True*, if the administrator can restrict, ban or unban chat members, or access supergroup statistics | [default to undefined]
**can_promote_members** | **boolean** | *True*, if the administrator can add new administrators with a subset of their own privileges or demote administrators that they have promoted, directly or indirectly (promoted by administrators that were appointed by the user) | [default to undefined]
**can_change_info** | **boolean** | *True*, if the user is allowed to change the chat title, photo and other settings | [default to undefined]
**can_invite_users** | **boolean** | *True*, if the user is allowed to invite new users to the chat | [default to undefined]
**can_post_stories** | **boolean** | *True*, if the administrator can post stories to the chat | [default to undefined]
**can_edit_stories** | **boolean** | *True*, if the administrator can edit stories posted by other users, post stories to the chat page, pin chat stories, and access the chat\&#39;s story archive | [default to undefined]
**can_delete_stories** | **boolean** | *True*, if the administrator can delete stories posted by other users | [default to undefined]
**can_post_messages** | **boolean** | *Optional*. *True*, if the administrator can post messages in the channel, or access channel statistics; for channels only | [optional] [default to undefined]
**can_edit_messages** | **boolean** | *Optional*. *True*, if the administrator can edit messages of other users and can pin messages; for channels only | [optional] [default to undefined]
**can_pin_messages** | **boolean** | *Optional*. *True*, if the user is allowed to pin messages; for groups and supergroups only | [optional] [default to undefined]
**can_manage_topics** | **boolean** | *Optional*. *True*, if the user is allowed to create, rename, close, and reopen forum topics; for supergroups only | [optional] [default to undefined]

## Example

```typescript
import { ChatAdministratorRights } from 'tele_rest';

const instance: ChatAdministratorRights = {
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
