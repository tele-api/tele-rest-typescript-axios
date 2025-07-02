# UnpinChatMessageRequest

Request parameters for unpinChatMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessageRequestChatId**](SendMessageRequestChatId.md) |  | [default to undefined]
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which the message will be unpinned | [optional] [default to undefined]
**message_id** | **number** | Identifier of the message to unpin. Required if *business\\_connection\\_id* is specified. If not specified, the most recent pinned message (by sending date) will be unpinned. | [optional] [default to undefined]

## Example

```typescript
import { UnpinChatMessageRequest } from 'tele_rest';

const instance: UnpinChatMessageRequest = {
    chat_id,
    business_connection_id,
    message_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
