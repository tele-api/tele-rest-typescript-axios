# PostEditMessageText200ResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message_id** | **number** | Unique message identifier inside this chat. In specific instances (e.g., message containing a video sent to a big chat), the server might automatically schedule a message instead of sending it immediately. In such cases, this field will be 0 and the relevant message will be unusable until it is actually sent | [default to undefined]
**date** | **number** | Date the message was sent in Unix time. It is always a positive number, representing a valid date. | [default to undefined]
**chat** | [**Chat**](Chat.md) |  | [default to undefined]
**message_thread_id** | **number** | *Optional*. Unique identifier of a message thread to which the message belongs; for supergroups only | [optional] [default to undefined]
**from** | [**User**](User.md) |  | [optional] [default to undefined]
**sender_chat** | [**Chat**](Chat.md) |  | [optional] [default to undefined]
**sender_boost_count** | **number** | *Optional*. If the sender of the message boosted the chat, the number of boosts added by the user | [optional] [default to undefined]
**sender_business_bot** | [**User**](User.md) |  | [optional] [default to undefined]
**business_connection_id** | **string** | *Optional*. Unique identifier of the business connection from which the message was received. If non-empty, the message belongs to a chat of the corresponding business account that is independent from any potential bot chat which might share the same identifier. | [optional] [default to undefined]
**forward_origin** | [**MessageOrigin**](MessageOrigin.md) |  | [optional] [default to undefined]
**is_topic_message** | **boolean** | *Optional*. *True*, if the message is sent to a forum topic | [optional] [default to true]
**is_automatic_forward** | **boolean** | *Optional*. *True*, if the message is a channel post that was automatically forwarded to the connected discussion group | [optional] [default to true]
**reply_to_message** | [**Message**](Message.md) |  | [optional] [default to undefined]
**external_reply** | [**ExternalReplyInfo**](ExternalReplyInfo.md) |  | [optional] [default to undefined]
**quote** | [**TextQuote**](TextQuote.md) |  | [optional] [default to undefined]
**reply_to_story** | [**Story**](Story.md) |  | [optional] [default to undefined]
**via_bot** | [**User**](User.md) |  | [optional] [default to undefined]
**edit_date** | **number** | *Optional*. Date the message was last edited in Unix time | [optional] [default to undefined]
**has_protected_content** | **boolean** | *Optional*. *True*, if the message can\&#39;t be forwarded | [optional] [default to true]
**is_from_offline** | **boolean** | *Optional*. True, if the message was sent by an implicit action, for example, as an away or a greeting business message, or as a scheduled message | [optional] [default to true]
**media_group_id** | **string** | *Optional*. The unique identifier of a media message group this message belongs to | [optional] [default to undefined]
**author_signature** | **string** | *Optional*. Signature of the post author for messages in channels, or the custom title of an anonymous group administrator | [optional] [default to undefined]
**paid_star_count** | **number** | *Optional*. The number of Telegram Stars that were paid by the sender of the message to send it | [optional] [default to undefined]
**text** | **string** | *Optional*. For text messages, the actual UTF-8 text of the message | [optional] [default to undefined]
**entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. For text messages, special entities like usernames, URLs, bot commands, etc. that appear in the text | [optional] [default to undefined]
**link_preview_options** | [**LinkPreviewOptions**](LinkPreviewOptions.md) |  | [optional] [default to undefined]
**effect_id** | **string** | *Optional*. Unique identifier of the message effect added to the message | [optional] [default to undefined]
**animation** | [**Animation**](Animation.md) |  | [optional] [default to undefined]
**audio** | [**Audio**](Audio.md) |  | [optional] [default to undefined]
**document** | [**Document**](Document.md) |  | [optional] [default to undefined]
**paid_media** | [**PaidMediaInfo**](PaidMediaInfo.md) |  | [optional] [default to undefined]
**photo** | [**Array&lt;PhotoSize&gt;**](PhotoSize.md) | *Optional*. Message is a photo, available sizes of the photo | [optional] [default to undefined]
**sticker** | [**Sticker**](Sticker.md) |  | [optional] [default to undefined]
**story** | [**Story**](Story.md) |  | [optional] [default to undefined]
**video** | [**Video**](Video.md) |  | [optional] [default to undefined]
**video_note** | [**VideoNote**](VideoNote.md) |  | [optional] [default to undefined]
**voice** | [**Voice**](Voice.md) |  | [optional] [default to undefined]
**caption** | **string** | *Optional*. Caption for the animation, audio, document, paid media, photo, video or voice | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. For messages with a caption, special entities like usernames, URLs, bot commands, etc. that appear in the caption | [optional] [default to undefined]
**show_caption_above_media** | **boolean** | *Optional*. True, if the caption must be shown above the message media | [optional] [default to true]
**has_media_spoiler** | **boolean** | *Optional*. *True*, if the message media is covered by a spoiler animation | [optional] [default to true]
**contact** | [**Contact**](Contact.md) |  | [optional] [default to undefined]
**dice** | [**Dice**](Dice.md) |  | [optional] [default to undefined]
**game** | [**Game**](Game.md) |  | [optional] [default to undefined]
**poll** | [**Poll**](Poll.md) |  | [optional] [default to undefined]
**venue** | [**Venue**](Venue.md) |  | [optional] [default to undefined]
**location** | [**Location**](Location.md) |  | [optional] [default to undefined]
**new_chat_members** | [**Array&lt;User&gt;**](User.md) | *Optional*. New members that were added to the group or supergroup and information about them (the bot itself may be one of these members) | [optional] [default to undefined]
**left_chat_member** | [**User**](User.md) |  | [optional] [default to undefined]
**new_chat_title** | **string** | *Optional*. A chat title was changed to this value | [optional] [default to undefined]
**new_chat_photo** | [**Array&lt;PhotoSize&gt;**](PhotoSize.md) | *Optional*. A chat photo was change to this value | [optional] [default to undefined]
**delete_chat_photo** | **boolean** | *Optional*. Service message: the chat photo was deleted | [optional] [default to true]
**group_chat_created** | **boolean** | *Optional*. Service message: the group has been created | [optional] [default to true]
**supergroup_chat_created** | **boolean** | *Optional*. Service message: the supergroup has been created. This field can\&#39;t be received in a message coming through updates, because bot can\&#39;t be a member of a supergroup when it is created. It can only be found in reply\\_to\\_message if someone replies to a very first message in a directly created supergroup. | [optional] [default to true]
**channel_chat_created** | **boolean** | *Optional*. Service message: the channel has been created. This field can\&#39;t be received in a message coming through updates, because bot can\&#39;t be a member of a channel when it is created. It can only be found in reply\\_to\\_message if someone replies to a very first message in a channel. | [optional] [default to true]
**message_auto_delete_timer_changed** | [**MessageAutoDeleteTimerChanged**](MessageAutoDeleteTimerChanged.md) |  | [optional] [default to undefined]
**migrate_to_chat_id** | **number** | *Optional*. The group has been migrated to a supergroup with the specified identifier. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a signed 64-bit integer or double-precision float type are safe for storing this identifier. | [optional] [default to undefined]
**migrate_from_chat_id** | **number** | *Optional*. The supergroup has been migrated from a group with the specified identifier. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a signed 64-bit integer or double-precision float type are safe for storing this identifier. | [optional] [default to undefined]
**pinned_message** | [**MaybeInaccessibleMessage**](MaybeInaccessibleMessage.md) |  | [optional] [default to undefined]
**invoice** | [**Invoice**](Invoice.md) |  | [optional] [default to undefined]
**successful_payment** | [**SuccessfulPayment**](SuccessfulPayment.md) |  | [optional] [default to undefined]
**refunded_payment** | [**RefundedPayment**](RefundedPayment.md) |  | [optional] [default to undefined]
**users_shared** | [**UsersShared**](UsersShared.md) |  | [optional] [default to undefined]
**chat_shared** | [**ChatShared**](ChatShared.md) |  | [optional] [default to undefined]
**gift** | [**GiftInfo**](GiftInfo.md) |  | [optional] [default to undefined]
**unique_gift** | [**UniqueGiftInfo**](UniqueGiftInfo.md) |  | [optional] [default to undefined]
**connected_website** | **string** | *Optional*. The domain name of the website on which the user has logged in. [More about Telegram Login »](https://core.telegram.org/widgets/login) | [optional] [default to undefined]
**write_access_allowed** | [**WriteAccessAllowed**](WriteAccessAllowed.md) |  | [optional] [default to undefined]
**passport_data** | [**PassportData**](PassportData.md) |  | [optional] [default to undefined]
**proximity_alert_triggered** | [**ProximityAlertTriggered**](ProximityAlertTriggered.md) |  | [optional] [default to undefined]
**boost_added** | [**ChatBoostAdded**](ChatBoostAdded.md) |  | [optional] [default to undefined]
**chat_background_set** | [**ChatBackground**](ChatBackground.md) |  | [optional] [default to undefined]
**forum_topic_created** | [**ForumTopicCreated**](ForumTopicCreated.md) |  | [optional] [default to undefined]
**forum_topic_edited** | [**ForumTopicEdited**](ForumTopicEdited.md) |  | [optional] [default to undefined]
**forum_topic_closed** | **any** |  | [optional] [default to undefined]
**forum_topic_reopened** | **any** |  | [optional] [default to undefined]
**general_forum_topic_hidden** | **any** |  | [optional] [default to undefined]
**general_forum_topic_unhidden** | **any** |  | [optional] [default to undefined]
**giveaway_created** | [**GiveawayCreated**](GiveawayCreated.md) |  | [optional] [default to undefined]
**giveaway** | [**Giveaway**](Giveaway.md) |  | [optional] [default to undefined]
**giveaway_winners** | [**GiveawayWinners**](GiveawayWinners.md) |  | [optional] [default to undefined]
**giveaway_completed** | [**GiveawayCompleted**](GiveawayCompleted.md) |  | [optional] [default to undefined]
**paid_message_price_changed** | [**PaidMessagePriceChanged**](PaidMessagePriceChanged.md) |  | [optional] [default to undefined]
**video_chat_scheduled** | [**VideoChatScheduled**](VideoChatScheduled.md) |  | [optional] [default to undefined]
**video_chat_started** | **any** |  | [optional] [default to undefined]
**video_chat_ended** | [**VideoChatEnded**](VideoChatEnded.md) |  | [optional] [default to undefined]
**video_chat_participants_invited** | [**VideoChatParticipantsInvited**](VideoChatParticipantsInvited.md) |  | [optional] [default to undefined]
**web_app_data** | [**WebAppData**](WebAppData.md) |  | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]

## Example

```typescript
import { PostEditMessageText200ResponseResult } from 'tele_rest';

const instance: PostEditMessageText200ResponseResult = {
    message_id,
    date,
    chat,
    message_thread_id,
    from,
    sender_chat,
    sender_boost_count,
    sender_business_bot,
    business_connection_id,
    forward_origin,
    is_topic_message,
    is_automatic_forward,
    reply_to_message,
    external_reply,
    quote,
    reply_to_story,
    via_bot,
    edit_date,
    has_protected_content,
    is_from_offline,
    media_group_id,
    author_signature,
    paid_star_count,
    text,
    entities,
    link_preview_options,
    effect_id,
    animation,
    audio,
    document,
    paid_media,
    photo,
    sticker,
    story,
    video,
    video_note,
    voice,
    caption,
    caption_entities,
    show_caption_above_media,
    has_media_spoiler,
    contact,
    dice,
    game,
    poll,
    venue,
    location,
    new_chat_members,
    left_chat_member,
    new_chat_title,
    new_chat_photo,
    delete_chat_photo,
    group_chat_created,
    supergroup_chat_created,
    channel_chat_created,
    message_auto_delete_timer_changed,
    migrate_to_chat_id,
    migrate_from_chat_id,
    pinned_message,
    invoice,
    successful_payment,
    refunded_payment,
    users_shared,
    chat_shared,
    gift,
    unique_gift,
    connected_website,
    write_access_allowed,
    passport_data,
    proximity_alert_triggered,
    boost_added,
    chat_background_set,
    forum_topic_created,
    forum_topic_edited,
    forum_topic_closed,
    forum_topic_reopened,
    general_forum_topic_hidden,
    general_forum_topic_unhidden,
    giveaway_created,
    giveaway,
    giveaway_winners,
    giveaway_completed,
    paid_message_price_changed,
    video_chat_scheduled,
    video_chat_started,
    video_chat_ended,
    video_chat_participants_invited,
    web_app_data,
    reply_markup,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
