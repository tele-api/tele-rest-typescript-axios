# TextQuote

This object contains information about the quoted part of a message that is replied to by the given message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **string** | Text of the quoted part of a message that is replied to by the given message | [default to undefined]
**position** | **number** | Approximate quote position in the original message in UTF-16 code units as specified by the sender | [default to undefined]
**entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. Special entities that appear in the quote. Currently, only *bold*, *italic*, *underline*, *strikethrough*, *spoiler*, and *custom\\_emoji* entities are kept in quotes. | [optional] [default to undefined]
**is_manual** | **boolean** | *Optional*. True, if the quote was chosen manually by the message sender. Otherwise, the quote was added automatically by the server. | [optional] [default to true]

## Example

```typescript
import { TextQuote } from 'tele_rest';

const instance: TextQuote = {
    text,
    position,
    entities,
    is_manual,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
