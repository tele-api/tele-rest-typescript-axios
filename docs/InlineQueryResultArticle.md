# InlineQueryResultArticle

Represents a link to an article or web page.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *article* | [default to 'article']
**id** | **string** | Unique identifier for this result, 1-64 Bytes | [default to undefined]
**title** | **string** | Title of the result | [default to undefined]
**input_message_content** | [**InputMessageContent**](InputMessageContent.md) |  | [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]
**url** | **string** | *Optional*. URL of the result | [optional] [default to undefined]
**description** | **string** | *Optional*. Short description of the result | [optional] [default to undefined]
**thumbnail_url** | **string** | *Optional*. Url of the thumbnail for the result | [optional] [default to undefined]
**thumbnail_width** | **number** | *Optional*. Thumbnail width | [optional] [default to undefined]
**thumbnail_height** | **number** | *Optional*. Thumbnail height | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultArticle } from 'tele_rest';

const instance: InlineQueryResultArticle = {
    type,
    id,
    title,
    input_message_content,
    reply_markup,
    url,
    description,
    thumbnail_url,
    thumbnail_width,
    thumbnail_height,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
