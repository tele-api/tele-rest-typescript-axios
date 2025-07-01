# InputTextMessageContent

Represents the [content](https://core.telegram.org/bots/api/#inputmessagecontent) of a text message to be sent as the result of an inline query.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message_text** | **string** | Text of the message to be sent, 1-4096 characters | [default to undefined]
**parse_mode** | **string** | *Optional*. Mode for parsing entities in the message text. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. List of special entities that appear in message text, which can be specified instead of *parse\\_mode* | [optional] [default to undefined]
**link_preview_options** | [**LinkPreviewOptions**](LinkPreviewOptions.md) |  | [optional] [default to undefined]

## Example

```typescript
import { InputTextMessageContent } from 'tele_rest';

const instance: InputTextMessageContent = {
    message_text,
    parse_mode,
    entities,
    link_preview_options,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
