# PostCloseForumTopicRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**PostRestrictChatMemberRequestChatId**](PostRestrictChatMemberRequestChatId.md) |  | [default to undefined]
**message_thread_id** | **number** | Unique identifier for the target message thread of the forum topic | [default to undefined]

## Example

```typescript
import { PostCloseForumTopicRequest } from 'tele_rest';

const instance: PostCloseForumTopicRequest = {
    chat_id,
    message_thread_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
