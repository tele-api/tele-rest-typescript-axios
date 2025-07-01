# ChatJoinRequest

Represents a join request sent to a chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat** | [**Chat**](Chat.md) |  | [default to undefined]
**from** | [**User**](User.md) |  | [default to undefined]
**user_chat_id** | **number** | Identifier of a private chat with the user who sent the join request. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a 64-bit integer or double-precision float type are safe for storing this identifier. The bot can use this identifier for 5 minutes to send messages until the join request is processed, assuming no other administrator contacted the user. | [default to undefined]
**date** | **number** | Date the request was sent in Unix time | [default to undefined]
**bio** | **string** | *Optional*. Bio of the user. | [optional] [default to undefined]
**invite_link** | [**ChatInviteLink**](ChatInviteLink.md) |  | [optional] [default to undefined]

## Example

```typescript
import { ChatJoinRequest } from 'tele_rest';

const instance: ChatJoinRequest = {
    chat,
    from,
    user_chat_id,
    date,
    bio,
    invite_link,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
