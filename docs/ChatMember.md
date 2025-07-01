# ChatMember

This object contains information about one member of a chat. Currently, the following 6 types of chat members are supported:  * [ChatMemberOwner](https://core.telegram.org/bots/api/#chatmemberowner) * [ChatMemberAdministrator](https://core.telegram.org/bots/api/#chatmemberadministrator) * [ChatMemberMember](https://core.telegram.org/bots/api/#chatmembermember) * [ChatMemberRestricted](https://core.telegram.org/bots/api/#chatmemberrestricted) * [ChatMemberLeft](https://core.telegram.org/bots/api/#chatmemberleft) * [ChatMemberBanned](https://core.telegram.org/bots/api/#chatmemberbanned)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **string** | The member\&#39;s status in the chat, always “kicked” | [default to 'kicked']
**user** | [**User**](User.md) |  | [default to undefined]
**is_anonymous** | **boolean** | *True*, if the user\&#39;s presence in the chat is hidden | [default to undefined]
**can_be_edited** | **boolean** | *True*, if the bot is allowed to edit administrator privileges of that user | [default to undefined]
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
**can_pin_messages** | **boolean** | *True*, if the user is allowed to pin messages | [default to undefined]
**can_manage_topics** | **boolean** | *True*, if the user is allowed to create forum topics | [default to undefined]
**until_date** | **number** | Date when restrictions will be lifted for this user; Unix time. If 0, then the user is banned forever | [default to undefined]
**is_member** | **boolean** | *True*, if the user is a member of the chat at the moment of the request | [default to undefined]
**can_send_messages** | **boolean** | *True*, if the user is allowed to send text messages, contacts, giveaways, giveaway winners, invoices, locations and venues | [default to undefined]
**can_send_audios** | **boolean** | *True*, if the user is allowed to send audios | [default to undefined]
**can_send_documents** | **boolean** | *True*, if the user is allowed to send documents | [default to undefined]
**can_send_photos** | **boolean** | *True*, if the user is allowed to send photos | [default to undefined]
**can_send_videos** | **boolean** | *True*, if the user is allowed to send videos | [default to undefined]
**can_send_video_notes** | **boolean** | *True*, if the user is allowed to send video notes | [default to undefined]
**can_send_voice_notes** | **boolean** | *True*, if the user is allowed to send voice notes | [default to undefined]
**can_send_polls** | **boolean** | *True*, if the user is allowed to send polls | [default to undefined]
**can_send_other_messages** | **boolean** | *True*, if the user is allowed to send animations, games, stickers and use inline bots | [default to undefined]
**can_add_web_page_previews** | **boolean** | *True*, if the user is allowed to add web page previews to their messages | [default to undefined]
**custom_title** | **string** | *Optional*. Custom title for this user | [optional] [default to undefined]
**can_post_messages** | **boolean** | *Optional*. *True*, if the administrator can post messages in the channel, or access channel statistics; for channels only | [optional] [default to undefined]
**can_edit_messages** | **boolean** | *Optional*. *True*, if the administrator can edit messages of other users and can pin messages; for channels only | [optional] [default to undefined]

## Example

```typescript
import { ChatMember } from 'tele_rest';

const instance: ChatMember = {
    status,
    user,
    is_anonymous,
    can_be_edited,
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
    can_pin_messages,
    can_manage_topics,
    until_date,
    is_member,
    can_send_messages,
    can_send_audios,
    can_send_documents,
    can_send_photos,
    can_send_videos,
    can_send_video_notes,
    can_send_voice_notes,
    can_send_polls,
    can_send_other_messages,
    can_add_web_page_previews,
    custom_title,
    can_post_messages,
    can_edit_messages,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
