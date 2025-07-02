# PostForwardMessagesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**PostSendMessageRequestChatId**](PostSendMessageRequestChatId.md) |  | [default to undefined]
**from_chat_id** | [**PostForwardMessagesRequestFromChatId**](PostForwardMessagesRequestFromChatId.md) |  | [default to undefined]
**message_ids** | **Array&lt;number&gt;** | A JSON-serialized list of 1-100 identifiers of messages in the chat *from\\_chat\\_id* to forward. The identifiers must be specified in a strictly increasing order. | [default to undefined]
**message_thread_id** | **number** | Unique identifier for the target message thread (topic) of the forum; for forum supergroups only | [optional] [default to undefined]
**disable_notification** | **boolean** | Sends the messages [silently](https://telegram.org/blog/channels-2-0#silent-messages). Users will receive a notification with no sound. | [optional] [default to undefined]
**protect_content** | **boolean** | Protects the contents of the forwarded messages from forwarding and saving | [optional] [default to undefined]

## Example

```typescript
import { PostForwardMessagesRequest } from 'tele_rest';

const instance: PostForwardMessagesRequest = {
    chat_id,
    from_chat_id,
    message_ids,
    message_thread_id,
    disable_notification,
    protect_content,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
