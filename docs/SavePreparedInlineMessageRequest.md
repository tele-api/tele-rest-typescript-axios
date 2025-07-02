# SavePreparedInlineMessageRequest

Request parameters for savePreparedInlineMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **number** | Unique identifier of the target user that can use the prepared message | [default to undefined]
**result** | [**InlineQueryResult**](InlineQueryResult.md) |  | [default to undefined]
**allow_user_chats** | **boolean** | Pass *True* if the message can be sent to private chats with users | [optional] [default to undefined]
**allow_bot_chats** | **boolean** | Pass *True* if the message can be sent to private chats with bots | [optional] [default to undefined]
**allow_group_chats** | **boolean** | Pass *True* if the message can be sent to group and supergroup chats | [optional] [default to undefined]
**allow_channel_chats** | **boolean** | Pass *True* if the message can be sent to channel chats | [optional] [default to undefined]

## Example

```typescript
import { SavePreparedInlineMessageRequest } from 'tele_rest';

const instance: SavePreparedInlineMessageRequest = {
    user_id,
    result,
    allow_user_chats,
    allow_bot_chats,
    allow_group_chats,
    allow_channel_chats,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
