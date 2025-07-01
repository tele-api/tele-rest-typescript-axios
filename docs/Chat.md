# Chat

This object represents a chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **number** | Unique identifier for this chat. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a signed 64-bit integer or double-precision float type are safe for storing this identifier. | [default to undefined]
**type** | **string** | Type of the chat, can be either “private”, “group”, “supergroup” or “channel” | [default to undefined]
**title** | **string** | *Optional*. Title, for supergroups, channels and group chats | [optional] [default to undefined]
**username** | **string** | *Optional*. Username, for private chats, supergroups and channels if available | [optional] [default to undefined]
**first_name** | **string** | *Optional*. First name of the other party in a private chat | [optional] [default to undefined]
**last_name** | **string** | *Optional*. Last name of the other party in a private chat | [optional] [default to undefined]
**is_forum** | **boolean** | *Optional*. *True*, if the supergroup chat is a forum (has [topics](https://telegram.org/blog/topics-in-groups-collectible-usernames#topics-in-groups) enabled) | [optional] [default to true]

## Example

```typescript
import { Chat } from 'tele_rest';

const instance: Chat = {
    id,
    type,
    title,
    username,
    first_name,
    last_name,
    is_forum,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
