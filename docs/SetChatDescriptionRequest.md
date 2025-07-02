# SetChatDescriptionRequest

Request parameters for setChatDescription

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessageRequestChatId**](SendMessageRequestChatId.md) |  | [default to undefined]
**description** | **string** | New chat description, 0-255 characters | [optional] [default to undefined]

## Example

```typescript
import { SetChatDescriptionRequest } from 'tele_rest';

const instance: SetChatDescriptionRequest = {
    chat_id,
    description,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
