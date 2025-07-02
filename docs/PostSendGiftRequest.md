# PostSendGiftRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gift_id** | **string** | Identifier of the gift | [default to undefined]
**user_id** | **number** | Required if *chat\\_id* is not specified. Unique identifier of the target user who will receive the gift. | [optional] [default to undefined]
**chat_id** | [**PostSendGiftRequestChatId**](PostSendGiftRequestChatId.md) |  | [optional] [default to undefined]
**pay_for_upgrade** | **boolean** | Pass *True* to pay for the gift upgrade from the bot\&#39;s balance, thereby making the upgrade free for the receiver | [optional] [default to undefined]
**text** | **string** | Text that will be shown along with the gift; 0-128 characters | [optional] [default to undefined]
**text_parse_mode** | **string** | Mode for parsing entities in the text. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. Entities other than “bold”, “italic”, “underline”, “strikethrough”, “spoiler”, and “custom\\_emoji” are ignored. | [optional] [default to undefined]
**text_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | A JSON-serialized list of special entities that appear in the gift text. It can be specified instead of *text\\_parse\\_mode*. Entities other than “bold”, “italic”, “underline”, “strikethrough”, “spoiler”, and “custom\\_emoji” are ignored. | [optional] [default to undefined]

## Example

```typescript
import { PostSendGiftRequest } from 'tele_rest';

const instance: PostSendGiftRequest = {
    gift_id,
    user_id,
    chat_id,
    pay_for_upgrade,
    text,
    text_parse_mode,
    text_entities,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
