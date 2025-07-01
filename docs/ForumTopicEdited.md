# ForumTopicEdited

This object represents a service message about an edited forum topic.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | *Optional*. New name of the topic, if it was edited | [optional] [default to undefined]
**icon_custom_emoji_id** | **string** | *Optional*. New identifier of the custom emoji shown as the topic icon, if it was edited; an empty string if the icon was removed | [optional] [default to undefined]

## Example

```typescript
import { ForumTopicEdited } from 'tele_rest';

const instance: ForumTopicEdited = {
    name,
    icon_custom_emoji_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
