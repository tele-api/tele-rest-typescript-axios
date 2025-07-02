# PostSetGameScoreRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **number** | User identifier | [default to undefined]
**score** | **number** | New score, must be non-negative | [default to undefined]
**force** | **boolean** | Pass *True* if the high score is allowed to decrease. This can be useful when fixing mistakes or banning cheaters | [optional] [default to undefined]
**disable_edit_message** | **boolean** | Pass *True* if the game message should not be automatically edited to include the current scoreboard | [optional] [default to undefined]
**chat_id** | **number** | Required if *inline\\_message\\_id* is not specified. Unique identifier for the target chat | [optional] [default to undefined]
**message_id** | **number** | Required if *inline\\_message\\_id* is not specified. Identifier of the sent message | [optional] [default to undefined]
**inline_message_id** | **string** | Required if *chat\\_id* and *message\\_id* are not specified. Identifier of the inline message | [optional] [default to undefined]

## Example

```typescript
import { PostSetGameScoreRequest } from 'tele_rest';

const instance: PostSetGameScoreRequest = {
    user_id,
    score,
    force,
    disable_edit_message,
    chat_id,
    message_id,
    inline_message_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
