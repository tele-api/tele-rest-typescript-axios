# UnbanChatSenderChatRequest

Request parameters for unbanChatSenderChat

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessageRequestChatId**](SendMessageRequestChatId.md) |  | [default to undefined]
**sender_chat_id** | **number** | Unique identifier of the target sender chat | [default to undefined]

## Example

```typescript
import { UnbanChatSenderChatRequest } from 'tele_rest';

const instance: UnbanChatSenderChatRequest = {
    chat_id,
    sender_chat_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
