# InlineQueryResultDocument

Represents a link to a file. By default, this file will be sent by the user with an optional caption. Alternatively, you can use *input\\_message\\_content* to send a message with the specified content instead of the file. Currently, only **.PDF** and **.ZIP** files can be sent using this method.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *document* | [default to 'document']
**id** | **string** | Unique identifier for this result, 1-64 bytes | [default to undefined]
**title** | **string** | Title for the result | [default to undefined]
**document_url** | **string** | A valid URL for the file | [default to undefined]
**mime_type** | **string** | MIME type of the content of the file, either “application/pdf” or “application/zip” | [default to undefined]
**caption** | **string** | *Optional*. Caption of the document to be sent, 0-1024 characters after entities parsing | [optional] [default to undefined]
**parse_mode** | **string** | *Optional*. Mode for parsing entities in the document caption. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**caption_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. List of special entities that appear in the caption, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**description** | **string** | *Optional*. Short description of the result | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]
**input_message_content** | [**InputMessageContent**](InputMessageContent.md) |  | [optional] [default to undefined]
**thumbnail_url** | **string** | *Optional*. URL of the thumbnail (JPEG only) for the file | [optional] [default to undefined]
**thumbnail_width** | **number** | *Optional*. Thumbnail width | [optional] [default to undefined]
**thumbnail_height** | **number** | *Optional*. Thumbnail height | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultDocument } from 'tele_rest';

const instance: InlineQueryResultDocument = {
    type,
    id,
    title,
    document_url,
    mime_type,
    caption,
    parse_mode,
    caption_entities,
    description,
    reply_markup,
    input_message_content,
    thumbnail_url,
    thumbnail_width,
    thumbnail_height,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
