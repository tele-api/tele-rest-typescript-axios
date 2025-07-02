# SetChatTitleRequest

Request parameters for setChatTitle

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessageRequestChatId**](SendMessageRequestChatId.md) |  | [default to undefined]
**title** | **string** | New chat title, 1-128 characters | [default to undefined]

## Example

```typescript
import { SetChatTitleRequest } from 'tele_rest';

const instance: SetChatTitleRequest = {
    chat_id,
    title,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
