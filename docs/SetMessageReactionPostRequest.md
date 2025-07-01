# SetMessageReactionPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessagePostRequestChatId**](SendMessagePostRequestChatId.md) |  | [default to undefined]
**message_id** | **number** | Identifier of the target message. If the message belongs to a media group, the reaction is set to the first non-deleted message in the group instead. | [default to undefined]
**reaction** | [**Array&lt;ReactionType&gt;**](ReactionType.md) | A JSON-serialized list of reaction types to set on the message. Currently, as non-premium users, bots can set up to one reaction per message. A custom emoji reaction can be used if it is either already present on the message or explicitly allowed by chat administrators. Paid reactions can\&#39;t be used by bots. | [optional] [default to undefined]
**is_big** | **boolean** | Pass *True* to set the reaction with a big animation | [optional] [default to undefined]

## Example

```typescript
import { SetMessageReactionPostRequest } from 'tele_rest';

const instance: SetMessageReactionPostRequest = {
    chat_id,
    message_id,
    reaction,
    is_big,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
