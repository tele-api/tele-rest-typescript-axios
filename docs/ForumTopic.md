# ForumTopic

This object represents a forum topic.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message_thread_id** | **number** | Unique identifier of the forum topic | [default to undefined]
**name** | **string** | Name of the topic | [default to undefined]
**icon_color** | **number** | Color of the topic icon in RGB format | [default to undefined]
**icon_custom_emoji_id** | **string** | *Optional*. Unique identifier of the custom emoji shown as the topic icon | [optional] [default to undefined]

## Example

```typescript
import { ForumTopic } from 'tele_rest';

const instance: ForumTopic = {
    message_thread_id,
    name,
    icon_color,
    icon_custom_emoji_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
