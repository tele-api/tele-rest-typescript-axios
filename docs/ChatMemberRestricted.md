# ChatMemberRestricted

Represents a [chat member](https://core.telegram.org/bots/api/#chatmember) that is under certain restrictions in the chat. Supergroups only.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **string** | The member\&#39;s status in the chat, always “restricted” | [default to 'restricted']
**user** | [**User**](User.md) |  | [default to undefined]
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
**can_change_info** | **boolean** | *True*, if the user is allowed to change the chat title, photo and other settings | [default to undefined]
**can_invite_users** | **boolean** | *True*, if the user is allowed to invite new users to the chat | [default to undefined]
**can_pin_messages** | **boolean** | *True*, if the user is allowed to pin messages | [default to undefined]
**can_manage_topics** | **boolean** | *True*, if the user is allowed to create forum topics | [default to undefined]
**until_date** | **number** | Date when restrictions will be lifted for this user; Unix time. If 0, then the user is restricted forever | [default to undefined]

## Example

```typescript
import { ChatMemberRestricted } from 'tele_rest';

const instance: ChatMemberRestricted = {
    status,
    user,
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
    can_change_info,
    can_invite_users,
    can_pin_messages,
    can_manage_topics,
    until_date,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
