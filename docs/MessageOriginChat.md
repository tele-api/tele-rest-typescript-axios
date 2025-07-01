# MessageOriginChat

The message was originally sent on behalf of a chat to a group chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the message origin, always “chat” | [default to 'chat']
**date** | **number** | Date the message was sent originally in Unix time | [default to undefined]
**sender_chat** | [**Chat**](Chat.md) |  | [default to undefined]
**author_signature** | **string** | *Optional*. For messages originally sent by an anonymous chat administrator, original message author signature | [optional] [default to undefined]

## Example

```typescript
import { MessageOriginChat } from 'tele_rest';

const instance: MessageOriginChat = {
    type,
    date,
    sender_chat,
    author_signature,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
