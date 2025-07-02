# PostDeleteBusinessMessagesRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which to delete the messages | [default to undefined]
**message_ids** | **Array&lt;number&gt;** | A JSON-serialized list of 1-100 identifiers of messages to delete. All messages must be from the same chat. See [deleteMessage](https://core.telegram.org/bots/api/#deletemessage) for limitations on which messages can be deleted | [default to undefined]

## Example

```typescript
import { PostDeleteBusinessMessagesRequest } from 'tele_rest';

const instance: PostDeleteBusinessMessagesRequest = {
    business_connection_id,
    message_ids,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
