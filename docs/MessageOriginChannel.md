# MessageOriginChannel

The message was originally sent to a channel chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the message origin, always “channel” | [default to 'channel']
**date** | **number** | Date the message was sent originally in Unix time | [default to undefined]
**chat** | [**Chat**](Chat.md) |  | [default to undefined]
**message_id** | **number** | Unique message identifier inside the chat | [default to undefined]
**author_signature** | **string** | *Optional*. Signature of the original post author | [optional] [default to undefined]

## Example

```typescript
import { MessageOriginChannel } from 'tele_rest';

const instance: MessageOriginChannel = {
    type,
    date,
    chat,
    message_id,
    author_signature,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
