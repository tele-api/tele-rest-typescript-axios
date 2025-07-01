# ChatFullInfo

This object contains full information about a chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **number** | Unique identifier for this chat. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a signed 64-bit integer or double-precision float type are safe for storing this identifier. | [default to undefined]
**type** | **string** | Type of the chat, can be either “private”, “group”, “supergroup” or “channel” | [default to undefined]
**accent_color_id** | **number** | Identifier of the accent color for the chat name and backgrounds of the chat photo, reply header, and link preview. See [accent colors](https://core.telegram.org/bots/api/#accent-colors) for more details. | [default to undefined]
**max_reaction_count** | **number** | The maximum number of reactions that can be set on a message in the chat | [default to undefined]
**accepted_gift_types** | [**AcceptedGiftTypes**](AcceptedGiftTypes.md) |  | [default to undefined]
**title** | **string** | *Optional*. Title, for supergroups, channels and group chats | [optional] [default to undefined]
**username** | **string** | *Optional*. Username, for private chats, supergroups and channels if available | [optional] [default to undefined]
**first_name** | **string** | *Optional*. First name of the other party in a private chat | [optional] [default to undefined]
**last_name** | **string** | *Optional*. Last name of the other party in a private chat | [optional] [default to undefined]
**is_forum** | **boolean** | *Optional*. *True*, if the supergroup chat is a forum (has [topics](https://telegram.org/blog/topics-in-groups-collectible-usernames#topics-in-groups) enabled) | [optional] [default to true]
**photo** | [**ChatPhoto**](ChatPhoto.md) |  | [optional] [default to undefined]
**active_usernames** | **Array&lt;string&gt;** | *Optional*. If non-empty, the list of all [active chat usernames](https://telegram.org/blog/topics-in-groups-collectible-usernames#collectible-usernames); for private chats, supergroups and channels | [optional] [default to undefined]
**birthdate** | [**Birthdate**](Birthdate.md) |  | [optional] [default to undefined]
**business_intro** | [**BusinessIntro**](BusinessIntro.md) |  | [optional] [default to undefined]
**business_location** | [**BusinessLocation**](BusinessLocation.md) |  | [optional] [default to undefined]
**business_opening_hours** | [**BusinessOpeningHours**](BusinessOpeningHours.md) |  | [optional] [default to undefined]
**personal_chat** | [**Chat**](Chat.md) |  | [optional] [default to undefined]
**available_reactions** | [**Array&lt;ReactionType&gt;**](ReactionType.md) | *Optional*. List of available reactions allowed in the chat. If omitted, then all [emoji reactions](https://core.telegram.org/bots/api/#reactiontypeemoji) are allowed. | [optional] [default to undefined]
**background_custom_emoji_id** | **string** | *Optional*. Custom emoji identifier of the emoji chosen by the chat for the reply header and link preview background | [optional] [default to undefined]
**profile_accent_color_id** | **number** | *Optional*. Identifier of the accent color for the chat\&#39;s profile background. See [profile accent colors](https://core.telegram.org/bots/api/#profile-accent-colors) for more details. | [optional] [default to undefined]
**profile_background_custom_emoji_id** | **string** | *Optional*. Custom emoji identifier of the emoji chosen by the chat for its profile background | [optional] [default to undefined]
**emoji_status_custom_emoji_id** | **string** | *Optional*. Custom emoji identifier of the emoji status of the chat or the other party in a private chat | [optional] [default to undefined]
**emoji_status_expiration_date** | **number** | *Optional*. Expiration date of the emoji status of the chat or the other party in a private chat, in Unix time, if any | [optional] [default to undefined]
**bio** | **string** | *Optional*. Bio of the other party in a private chat | [optional] [default to undefined]
**has_private_forwards** | **boolean** | *Optional*. *True*, if privacy settings of the other party in the private chat allows to use &#x60;tg://user?id&#x3D;&lt;user_id&gt;&#x60; links only in chats with the user | [optional] [default to true]
**has_restricted_voice_and_video_messages** | **boolean** | *Optional*. *True*, if the privacy settings of the other party restrict sending voice and video note messages in the private chat | [optional] [default to true]
**join_to_send_messages** | **boolean** | *Optional*. *True*, if users need to join the supergroup before they can send messages | [optional] [default to true]
**join_by_request** | **boolean** | *Optional*. *True*, if all users directly joining the supergroup without using an invite link need to be approved by supergroup administrators | [optional] [default to true]
**description** | **string** | *Optional*. Description, for groups, supergroups and channel chats | [optional] [default to undefined]
**invite_link** | **string** | *Optional*. Primary invite link, for groups, supergroups and channel chats | [optional] [default to undefined]
**pinned_message** | [**Message**](Message.md) |  | [optional] [default to undefined]
**permissions** | [**ChatPermissions**](ChatPermissions.md) |  | [optional] [default to undefined]
**can_send_paid_media** | **boolean** | *Optional*. *True*, if paid media messages can be sent or forwarded to the channel chat. The field is available only for channel chats. | [optional] [default to true]
**slow_mode_delay** | **number** | *Optional*. For supergroups, the minimum allowed delay between consecutive messages sent by each unprivileged user; in seconds | [optional] [default to undefined]
**unrestrict_boost_count** | **number** | *Optional*. For supergroups, the minimum number of boosts that a non-administrator user needs to add in order to ignore slow mode and chat permissions | [optional] [default to undefined]
**message_auto_delete_time** | **number** | *Optional*. The time after which all messages sent to the chat will be automatically deleted; in seconds | [optional] [default to undefined]
**has_aggressive_anti_spam_enabled** | **boolean** | *Optional*. *True*, if aggressive anti-spam checks are enabled in the supergroup. The field is only available to chat administrators. | [optional] [default to true]
**has_hidden_members** | **boolean** | *Optional*. *True*, if non-administrators can only get the list of bots and administrators in the chat | [optional] [default to true]
**has_protected_content** | **boolean** | *Optional*. *True*, if messages from the chat can\&#39;t be forwarded to other chats | [optional] [default to true]
**has_visible_history** | **boolean** | *Optional*. *True*, if new chat members will have access to old messages; available only to chat administrators | [optional] [default to true]
**sticker_set_name** | **string** | *Optional*. For supergroups, name of the group sticker set | [optional] [default to undefined]
**can_set_sticker_set** | **boolean** | *Optional*. *True*, if the bot can change the group sticker set | [optional] [default to true]
**custom_emoji_sticker_set_name** | **string** | *Optional*. For supergroups, the name of the group\&#39;s custom emoji sticker set. Custom emoji from this set can be used by all users and bots in the group. | [optional] [default to undefined]
**linked_chat_id** | **number** | *Optional*. Unique identifier for the linked chat, i.e. the discussion group identifier for a channel and vice versa; for supergroups and channel chats. This identifier may be greater than 32 bits and some programming languages may have difficulty/silent defects in interpreting it. But it is smaller than 52 bits, so a signed 64 bit integer or double-precision float type are safe for storing this identifier. | [optional] [default to undefined]
**location** | [**ChatLocation**](ChatLocation.md) |  | [optional] [default to undefined]

## Example

```typescript
import { ChatFullInfo } from 'tele_rest';

const instance: ChatFullInfo = {
    id,
    type,
    accent_color_id,
    max_reaction_count,
    accepted_gift_types,
    title,
    username,
    first_name,
    last_name,
    is_forum,
    photo,
    active_usernames,
    birthdate,
    business_intro,
    business_location,
    business_opening_hours,
    personal_chat,
    available_reactions,
    background_custom_emoji_id,
    profile_accent_color_id,
    profile_background_custom_emoji_id,
    emoji_status_custom_emoji_id,
    emoji_status_expiration_date,
    bio,
    has_private_forwards,
    has_restricted_voice_and_video_messages,
    join_to_send_messages,
    join_by_request,
    description,
    invite_link,
    pinned_message,
    permissions,
    can_send_paid_media,
    slow_mode_delay,
    unrestrict_boost_count,
    message_auto_delete_time,
    has_aggressive_anti_spam_enabled,
    has_hidden_members,
    has_protected_content,
    has_visible_history,
    sticker_set_name,
    can_set_sticker_set,
    custom_emoji_sticker_set_name,
    linked_chat_id,
    location,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
