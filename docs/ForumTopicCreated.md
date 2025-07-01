# ForumTopicCreated

This object represents a service message about a new forum topic created in the chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | Name of the topic | [default to undefined]
**icon_color** | **number** | Color of the topic icon in RGB format | [default to undefined]
**icon_custom_emoji_id** | **string** | *Optional*. Unique identifier of the custom emoji shown as the topic icon | [optional] [default to undefined]

## Example

```typescript
import { ForumTopicCreated } from 'tele_rest';

const instance: ForumTopicCreated = {
    name,
    icon_color,
    icon_custom_emoji_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
