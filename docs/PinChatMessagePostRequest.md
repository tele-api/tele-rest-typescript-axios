# PinChatMessagePostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessagePostRequestChatId**](SendMessagePostRequestChatId.md) |  | [default to undefined]
**message_id** | **number** | Identifier of a message to pin | [default to undefined]
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which the message will be pinned | [optional] [default to undefined]
**disable_notification** | **boolean** | Pass *True* if it is not necessary to send a notification to all chat members about the new pinned message. Notifications are always disabled in channels and private chats. | [optional] [default to undefined]

## Example

```typescript
import { PinChatMessagePostRequest } from 'tele_rest';

const instance: PinChatMessagePostRequest = {
    chat_id,
    message_id,
    business_connection_id,
    disable_notification,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
