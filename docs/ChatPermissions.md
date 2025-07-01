# ChatPermissions

Describes actions that a non-administrator user is allowed to take in a chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**can_send_messages** | **boolean** | *Optional*. *True*, if the user is allowed to send text messages, contacts, giveaways, giveaway winners, invoices, locations and venues | [optional] [default to undefined]
**can_send_audios** | **boolean** | *Optional*. *True*, if the user is allowed to send audios | [optional] [default to undefined]
**can_send_documents** | **boolean** | *Optional*. *True*, if the user is allowed to send documents | [optional] [default to undefined]
**can_send_photos** | **boolean** | *Optional*. *True*, if the user is allowed to send photos | [optional] [default to undefined]
**can_send_videos** | **boolean** | *Optional*. *True*, if the user is allowed to send videos | [optional] [default to undefined]
**can_send_video_notes** | **boolean** | *Optional*. *True*, if the user is allowed to send video notes | [optional] [default to undefined]
**can_send_voice_notes** | **boolean** | *Optional*. *True*, if the user is allowed to send voice notes | [optional] [default to undefined]
**can_send_polls** | **boolean** | *Optional*. *True*, if the user is allowed to send polls | [optional] [default to undefined]
**can_send_other_messages** | **boolean** | *Optional*. *True*, if the user is allowed to send animations, games, stickers and use inline bots | [optional] [default to undefined]
**can_add_web_page_previews** | **boolean** | *Optional*. *True*, if the user is allowed to add web page previews to their messages | [optional] [default to undefined]
**can_change_info** | **boolean** | *Optional*. *True*, if the user is allowed to change the chat title, photo and other settings. Ignored in public supergroups | [optional] [default to undefined]
**can_invite_users** | **boolean** | *Optional*. *True*, if the user is allowed to invite new users to the chat | [optional] [default to undefined]
**can_pin_messages** | **boolean** | *Optional*. *True*, if the user is allowed to pin messages. Ignored in public supergroups | [optional] [default to undefined]
**can_manage_topics** | **boolean** | *Optional*. *True*, if the user is allowed to create forum topics. If omitted defaults to the value of can\\_pin\\_messages | [optional] [default to undefined]

## Example

```typescript
import { ChatPermissions } from 'tele_rest';

const instance: ChatPermissions = {
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
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
