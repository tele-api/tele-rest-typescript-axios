# SwitchInlineQueryChosenChat

This object represents an inline button that switches the current user to inline mode in a chosen chat, with an optional default inline query.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**query** | **string** | *Optional*. The default inline query to be inserted in the input field. If left empty, only the bot\&#39;s username will be inserted | [optional] [default to undefined]
**allow_user_chats** | **boolean** | *Optional*. True, if private chats with users can be chosen | [optional] [default to undefined]
**allow_bot_chats** | **boolean** | *Optional*. True, if private chats with bots can be chosen | [optional] [default to undefined]
**allow_group_chats** | **boolean** | *Optional*. True, if group and supergroup chats can be chosen | [optional] [default to undefined]
**allow_channel_chats** | **boolean** | *Optional*. True, if channel chats can be chosen | [optional] [default to undefined]

## Example

```typescript
import { SwitchInlineQueryChosenChat } from 'tele_rest';

const instance: SwitchInlineQueryChosenChat = {
    query,
    allow_user_chats,
    allow_bot_chats,
    allow_group_chats,
    allow_channel_chats,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
