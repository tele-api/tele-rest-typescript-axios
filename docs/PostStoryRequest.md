# PostStoryRequest

Request parameters for postStory

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection | [default to undefined]
**content** | [**InputStoryContent**](InputStoryContent.md) |  | [default to undefined]
**active_period** | **number** | Period after which the story is moved to the archive, in seconds; must be one of &#x60;6 * 3600&#x60;, &#x60;12 * 3600&#x60;, &#x60;86400&#x60;, or &#x60;2 * 86400&#x60; | [default to undefined]
**caption** | **string** | Caption of the story, 0-2048 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | Mode for parsing entities in the story caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | A JSON-serialized list of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**areas** | [**Array&lt;StoryArea&gt;**](StoryArea.md) | A JSON-serialized list of clickable areas to be shown on the story | [optional] [default to undefined]
**post_to_chat_page** | **boolean** | Pass *True* to keep the story accessible after it expires | [optional] [default to undefined]
**protect_content** | **boolean** | Pass *True* if the content of the story must be protected from forwarding and screenshotting | [optional] [default to undefined]

## Example

```typescript
import { PostStoryRequest } from 'tele_rest';

const instance: PostStoryRequest = {
    business_connection_id,
    content,
    active_period,
    caption,
    parse_mode,
    caption_entities,
    areas,
    post_to_chat_page,
    protect_content,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
