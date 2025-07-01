# SetChatDescriptionPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessagePostRequestChatId**](SendMessagePostRequestChatId.md) |  | [default to undefined]
**description** | **string** | New chat description, 0-255 characters | [optional] [default to undefined]

## Example

```typescript
import { SetChatDescriptionPostRequest } from 'tele_rest';

const instance: SetChatDescriptionPostRequest = {
    chat_id,
    description,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
