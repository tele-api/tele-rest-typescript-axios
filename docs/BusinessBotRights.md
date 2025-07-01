# BusinessBotRights

Represents the rights of a business bot.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**can_reply** | **boolean** | *Optional*. True, if the bot can send and edit messages in the private chats that had incoming messages in the last 24 hours | [optional] [default to true]
**can_read_messages** | **boolean** | *Optional*. True, if the bot can mark incoming private messages as read | [optional] [default to true]
**can_delete_sent_messages** | **boolean** | *Optional*. True, if the bot can delete messages sent by the bot | [optional] [default to true]
**can_delete_all_messages** | **boolean** | *Optional*. True, if the bot can delete all private messages in managed chats | [optional] [default to true]
**can_edit_name** | **boolean** | *Optional*. True, if the bot can edit the first and last name of the business account | [optional] [default to true]
**can_edit_bio** | **boolean** | *Optional*. True, if the bot can edit the bio of the business account | [optional] [default to true]
**can_edit_profile_photo** | **boolean** | *Optional*. True, if the bot can edit the profile photo of the business account | [optional] [default to true]
**can_edit_username** | **boolean** | *Optional*. True, if the bot can edit the username of the business account | [optional] [default to true]
**can_change_gift_settings** | **boolean** | *Optional*. True, if the bot can change the privacy settings pertaining to gifts for the business account | [optional] [default to true]
**can_view_gifts_and_stars** | **boolean** | *Optional*. True, if the bot can view gifts and the amount of Telegram Stars owned by the business account | [optional] [default to true]
**can_convert_gifts_to_stars** | **boolean** | *Optional*. True, if the bot can convert regular gifts owned by the business account to Telegram Stars | [optional] [default to true]
**can_transfer_and_upgrade_gifts** | **boolean** | *Optional*. True, if the bot can transfer and upgrade gifts owned by the business account | [optional] [default to true]
**can_transfer_stars** | **boolean** | *Optional*. True, if the bot can transfer Telegram Stars received by the business account to its own account, or use them to upgrade and transfer gifts | [optional] [default to true]
**can_manage_stories** | **boolean** | *Optional*. True, if the bot can post, edit and delete stories on behalf of the business account | [optional] [default to true]

## Example

```typescript
import { BusinessBotRights } from 'tele_rest';

const instance: BusinessBotRights = {
    can_reply,
    can_read_messages,
    can_delete_sent_messages,
    can_delete_all_messages,
    can_edit_name,
    can_edit_bio,
    can_edit_profile_photo,
    can_edit_username,
    can_change_gift_settings,
    can_view_gifts_and_stars,
    can_convert_gifts_to_stars,
    can_transfer_and_upgrade_gifts,
    can_transfer_stars,
    can_manage_stories,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
