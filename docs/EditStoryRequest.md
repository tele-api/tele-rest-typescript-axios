# EditStoryRequest

Request parameters for editStory

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection | [default to undefined]
**story_id** | **number** | Unique identifier of the story to edit | [default to undefined]
**content** | [**InputStoryContent**](InputStoryContent.md) |  | [default to undefined]
**caption** | **string** | Caption of the story, 0-2048 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | Mode for parsing entities in the story caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | A JSON-serialized list of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**areas** | [**Array&lt;StoryArea&gt;**](StoryArea.md) | A JSON-serialized list of clickable areas to be shown on the story | [optional] [default to undefined]

## Example

```typescript
import { EditStoryRequest } from 'tele_rest';

const instance: EditStoryRequest = {
    business_connection_id,
    story_id,
    content,
    caption,
    parse_mode,
    caption_entities,
    areas,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
