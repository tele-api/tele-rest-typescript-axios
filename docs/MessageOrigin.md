# MessageOrigin

This object describes the origin of a message. It can be one of  * [MessageOriginUser](https://core.telegram.org/bots/api/#messageoriginuser) * [MessageOriginHiddenUser](https://core.telegram.org/bots/api/#messageoriginhiddenuser) * [MessageOriginChat](https://core.telegram.org/bots/api/#messageoriginchat) * [MessageOriginChannel](https://core.telegram.org/bots/api/#messageoriginchannel)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the message origin, always “channel” | [default to 'channel']
**date** | **number** | Date the message was sent originally in Unix time | [default to undefined]
**sender_user** | [**User**](User.md) |  | [default to undefined]
**sender_user_name** | **string** | Name of the user that sent the message originally | [default to undefined]
**sender_chat** | [**Chat**](Chat.md) |  | [default to undefined]
**chat** | [**Chat**](Chat.md) |  | [default to undefined]
**message_id** | **number** | Unique message identifier inside the chat | [default to undefined]
**author_signature** | **string** | *Optional*. Signature of the original post author | [optional] [default to undefined]

## Example

```typescript
import { MessageOrigin } from 'tele_rest';

const instance: MessageOrigin = {
    type,
    date,
    sender_user,
    sender_user_name,
    sender_chat,
    chat,
    message_id,
    author_signature,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
