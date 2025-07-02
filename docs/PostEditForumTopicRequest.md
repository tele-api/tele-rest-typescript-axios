# PostEditForumTopicRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**PostRestrictChatMemberRequestChatId**](PostRestrictChatMemberRequestChatId.md) |  | [default to undefined]
**message_thread_id** | **number** | Unique identifier for the target message thread of the forum topic | [default to undefined]
**name** | **string** | New topic name, 0-128 characters. If not specified or empty, the current name of the topic will be kept | [optional] [default to undefined]
**icon_custom_emoji_id** | **string** | New unique identifier of the custom emoji shown as the topic icon. Use [getForumTopicIconStickers](https://core.telegram.org/bots/api/#getforumtopiciconstickers) to get all allowed custom emoji identifiers. Pass an empty string to remove the icon. If not specified, the current icon will be kept | [optional] [default to undefined]

## Example

```typescript
import { PostEditForumTopicRequest } from 'tele_rest';

const instance: PostEditForumTopicRequest = {
    chat_id,
    message_thread_id,
    name,
    icon_custom_emoji_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
