# PostForwardMessageRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**PostSendMessageRequestChatId**](PostSendMessageRequestChatId.md) |  | [default to undefined]
**from_chat_id** | [**PostForwardMessageRequestFromChatId**](PostForwardMessageRequestFromChatId.md) |  | [default to undefined]
**message_id** | **number** | Message identifier in the chat specified in *from\\_chat\\_id* | [default to undefined]
**message_thread_id** | **number** | Unique identifier for the target message thread (topic) of the forum; for forum supergroups only | [optional] [default to undefined]
**video_start_timestamp** | **number** | New start timestamp for the forwarded video in the message | [optional] [default to undefined]
**disable_notification** | **boolean** | Sends the message [silently](https://telegram.org/blog/channels-2-0#silent-messages). Users will receive a notification with no sound. | [optional] [default to undefined]
**protect_content** | **boolean** | Protects the contents of the forwarded message from forwarding and saving | [optional] [default to undefined]

## Example

```typescript
import { PostForwardMessageRequest } from 'tele_rest';

const instance: PostForwardMessageRequest = {
    chat_id,
    from_chat_id,
    message_id,
    message_thread_id,
    video_start_timestamp,
    disable_notification,
    protect_content,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
