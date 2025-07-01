# ReplyParameters

Describes reply parameters for the message that is being sent.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message_id** | **number** | Identifier of the message that will be replied to in the current chat, or in the chat *chat\\_id* if it is specified | [default to undefined]
**chat_id** | [**ReplyParametersChatId**](ReplyParametersChatId.md) |  | [optional] [default to undefined]
**allow_sending_without_reply** | **boolean** | *Optional*. Pass *True* if the message should be sent even if the specified message to be replied to is not found. Always *False* for replies in another chat or forum topic. Always *True* for messages sent on behalf of a business account. | [optional] [default to undefined]
**quote** | **string** | *Optional*. Quoted part of the message to be replied to; 0-1024 characters after entities parsing. The quote must be an exact substring of the message to be replied to, including *bold*, *italic*, *underline*, *strikethrough*, *spoiler*, and *custom\\_emoji* entities. The message will fail to send if the quote isn\&#39;t found in the original message. | [optional] [default to undefined]
**quote_parse_mode** | **string** | *Optional*. Mode for parsing entities in the quote. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**quote_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. A JSON-serialized list of special entities that appear in the quote. It can be specified instead of *quote\\_parse\\_mode*. | [optional] [default to undefined]
**quote_position** | **number** | *Optional*. Position of the quote in the original message in UTF-16 code units | [optional] [default to undefined]

## Example

```typescript
import { ReplyParameters } from 'tele_rest';

const instance: ReplyParameters = {
    message_id,
    chat_id,
    allow_sending_without_reply,
    quote,
    quote_parse_mode,
    quote_entities,
    quote_position,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
