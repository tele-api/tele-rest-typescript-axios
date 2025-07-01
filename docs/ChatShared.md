# ChatShared

This object contains information about a chat that was shared with the bot using a [KeyboardButtonRequestChat](https://core.telegram.org/bots/api/#keyboardbuttonrequestchat) button.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **number** | Identifier of the request | [default to undefined]
**chat_id** | **number** | Identifier of the shared chat. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a 64-bit integer or double-precision float type are safe for storing this identifier. The bot may not have access to the chat and could be unable to use this identifier, unless the chat is already known to the bot by some other means. | [default to undefined]
**title** | **string** | *Optional*. Title of the chat, if the title was requested by the bot. | [optional] [default to undefined]
**username** | **string** | *Optional*. Username of the chat, if the username was requested by the bot and available. | [optional] [default to undefined]
**photo** | [**Array&lt;PhotoSize&gt;**](PhotoSize.md) | *Optional*. Available sizes of the chat photo, if the photo was requested by the bot | [optional] [default to undefined]

## Example

```typescript
import { ChatShared } from 'tele_rest';

const instance: ChatShared = {
    request_id,
    chat_id,
    title,
    username,
    photo,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
