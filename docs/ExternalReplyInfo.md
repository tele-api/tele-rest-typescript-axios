# ExternalReplyInfo

This object contains information about a message that is being replied to, which may come from another chat or forum topic.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**origin** | [**MessageOrigin**](MessageOrigin.md) |  | [default to undefined]
**chat** | [**Chat**](Chat.md) |  | [optional] [default to undefined]
**message_id** | **number** | *Optional*. Unique message identifier inside the original chat. Available only if the original chat is a supergroup or a channel. | [optional] [default to undefined]
**link_preview_options** | [**LinkPreviewOptions**](LinkPreviewOptions.md) |  | [optional] [default to undefined]
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
**has_media_spoiler** | **boolean** | *Optional*. *True*, if the message media is covered by a spoiler animation | [optional] [default to true]
**contact** | [**Contact**](Contact.md) |  | [optional] [default to undefined]
**dice** | [**Dice**](Dice.md) |  | [optional] [default to undefined]
**game** | [**Game**](Game.md) |  | [optional] [default to undefined]
**giveaway** | [**Giveaway**](Giveaway.md) |  | [optional] [default to undefined]
**giveaway_winners** | [**GiveawayWinners**](GiveawayWinners.md) |  | [optional] [default to undefined]
**invoice** | [**Invoice**](Invoice.md) |  | [optional] [default to undefined]
**location** | [**Location**](Location.md) |  | [optional] [default to undefined]
**poll** | [**Poll**](Poll.md) |  | [optional] [default to undefined]
**venue** | [**Venue**](Venue.md) |  | [optional] [default to undefined]

## Example

```typescript
import { ExternalReplyInfo } from 'tele_rest';

const instance: ExternalReplyInfo = {
    origin,
    chat,
    message_id,
    link_preview_options,
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
    has_media_spoiler,
    contact,
    dice,
    game,
    giveaway,
    giveaway_winners,
    invoice,
    location,
    poll,
    venue,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
