# PostVerifyChatRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**PostSendMessageRequestChatId**](PostSendMessageRequestChatId.md) |  | [default to undefined]
**custom_description** | **string** | Custom description for the verification; 0-70 characters. Must be empty if the organization isn\&#39;t allowed to provide a custom verification description. | [optional] [default to undefined]

## Example

```typescript
import { PostVerifyChatRequest } from 'tele_rest';

const instance: PostVerifyChatRequest = {
    chat_id,
    custom_description,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
