# User

This object represents a Telegram user or bot.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **number** | Unique identifier for this user or bot. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a 64-bit integer or double-precision float type are safe for storing this identifier. | [default to undefined]
**is_bot** | **boolean** | *True*, if this user is a bot | [default to undefined]
**first_name** | **string** | User\&#39;s or bot\&#39;s first name | [default to undefined]
**last_name** | **string** | *Optional*. User\&#39;s or bot\&#39;s last name | [optional] [default to undefined]
**username** | **string** | *Optional*. User\&#39;s or bot\&#39;s username | [optional] [default to undefined]
**language_code** | **string** | *Optional*. [IETF language tag](https://en.wikipedia.org/wiki/IETF_language_tag) of the user\&#39;s language | [optional] [default to undefined]
**is_premium** | **boolean** | *Optional*. *True*, if this user is a Telegram Premium user | [optional] [default to true]
**added_to_attachment_menu** | **boolean** | *Optional*. *True*, if this user added the bot to the attachment menu | [optional] [default to true]
**can_join_groups** | **boolean** | *Optional*. *True*, if the bot can be invited to groups. Returned only in [getMe](https://core.telegram.org/bots/api/#getme). | [optional] [default to undefined]
**can_read_all_group_messages** | **boolean** | *Optional*. *True*, if [privacy mode](https://core.telegram.org/bots/features#privacy-mode) is disabled for the bot. Returned only in [getMe](https://core.telegram.org/bots/api/#getme). | [optional] [default to undefined]
**supports_inline_queries** | **boolean** | *Optional*. *True*, if the bot supports inline queries. Returned only in [getMe](https://core.telegram.org/bots/api/#getme). | [optional] [default to undefined]
**can_connect_to_business** | **boolean** | *Optional*. *True*, if the bot can be connected to a Telegram Business account to receive its messages. Returned only in [getMe](https://core.telegram.org/bots/api/#getme). | [optional] [default to undefined]
**has_main_web_app** | **boolean** | *Optional*. *True*, if the bot has a main Web App. Returned only in [getMe](https://core.telegram.org/bots/api/#getme). | [optional] [default to undefined]

## Example

```typescript
import { User } from 'tele_rest';

const instance: User = {
    id,
    is_bot,
    first_name,
    last_name,
    username,
    language_code,
    is_premium,
    added_to_attachment_menu,
    can_join_groups,
    can_read_all_group_messages,
    supports_inline_queries,
    can_connect_to_business,
    has_main_web_app,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
