# BusinessMessagesDeleted

This object is received when messages are deleted from a connected business account.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection | [default to undefined]
**chat** | [**Chat**](Chat.md) |  | [default to undefined]
**message_ids** | **Array&lt;number&gt;** | The list of identifiers of deleted messages in the chat of the business account | [default to undefined]

## Example

```typescript
import { BusinessMessagesDeleted } from 'tele_rest';

const instance: BusinessMessagesDeleted = {
    business_connection_id,
    chat,
    message_ids,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
