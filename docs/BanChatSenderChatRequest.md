# BanChatSenderChatRequest

Request parameters for banChatSenderChat

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessageRequestChatId**](SendMessageRequestChatId.md) |  | [default to undefined]
**sender_chat_id** | **number** | Unique identifier of the target sender chat | [default to undefined]

## Example

```typescript
import { BanChatSenderChatRequest } from 'tele_rest';

const instance: BanChatSenderChatRequest = {
    chat_id,
    sender_chat_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
