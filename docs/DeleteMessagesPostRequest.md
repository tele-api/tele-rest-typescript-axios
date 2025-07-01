# DeleteMessagesPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessagePostRequestChatId**](SendMessagePostRequestChatId.md) |  | [default to undefined]
**message_ids** | **Array&lt;number&gt;** | A JSON-serialized list of 1-100 identifiers of messages to delete. See [deleteMessage](https://core.telegram.org/bots/api/#deletemessage) for limitations on which messages can be deleted | [default to undefined]

## Example

```typescript
import { DeleteMessagesPostRequest } from 'tele_rest';

const instance: DeleteMessagesPostRequest = {
    chat_id,
    message_ids,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
