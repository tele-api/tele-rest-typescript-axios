# InputPollOption

This object contains information about one answer option in a poll to be sent.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **string** | Option text, 1-100 characters | [default to undefined]
**text_parse_mode** | **string** | *Optional*. Mode for parsing entities in the text. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. Currently, only custom emoji entities are allowed | [optional] [default to undefined]
**text_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. A JSON-serialized list of special entities that appear in the poll option text. It can be specified instead of *text\\_parse\\_mode* | [optional] [default to undefined]

## Example

```typescript
import { InputPollOption } from 'tele_rest';

const instance: InputPollOption = {
    text,
    text_parse_mode,
    text_entities,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
