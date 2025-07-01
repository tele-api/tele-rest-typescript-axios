# ReadBusinessMessagePostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which to read the message | [default to undefined]
**chat_id** | **number** | Unique identifier of the chat in which the message was received. The chat must have been active in the last 24 hours. | [default to undefined]
**message_id** | **number** | Unique identifier of the message to mark as read | [default to undefined]

## Example

```typescript
import { ReadBusinessMessagePostRequest } from 'tele_rest';

const instance: ReadBusinessMessagePostRequest = {
    business_connection_id,
    chat_id,
    message_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
