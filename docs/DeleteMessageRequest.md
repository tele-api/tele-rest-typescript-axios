# DeleteMessageRequest

Request parameters for deleteMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessageRequestChatId**](SendMessageRequestChatId.md) |  | [default to undefined]
**message_id** | **number** | Identifier of the message to delete | [default to undefined]

## Example

```typescript
import { DeleteMessageRequest } from 'tele_rest';

const instance: DeleteMessageRequest = {
    chat_id,
    message_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
