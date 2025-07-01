# GetGameHighScoresPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **number** | Target user id | [default to undefined]
**chat_id** | **number** | Required if *inline\\_message\\_id* is not specified. Unique identifier for the target chat | [optional] [default to undefined]
**message_id** | **number** | Required if *inline\\_message\\_id* is not specified. Identifier of the sent message | [optional] [default to undefined]
**inline_message_id** | **string** | Required if *chat\\_id* and *message\\_id* are not specified. Identifier of the inline message | [optional] [default to undefined]

## Example

```typescript
import { GetGameHighScoresPostRequest } from 'tele_rest';

const instance: GetGameHighScoresPostRequest = {
    user_id,
    chat_id,
    message_id,
    inline_message_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
