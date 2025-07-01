# MessageReactionCountUpdated

This object represents reaction changes on a message with anonymous reactions.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat** | [**Chat**](Chat.md) |  | [default to undefined]
**message_id** | **number** | Unique message identifier inside the chat | [default to undefined]
**date** | **number** | Date of the change in Unix time | [default to undefined]
**reactions** | [**Array&lt;ReactionCount&gt;**](ReactionCount.md) | List of reactions that are present on the message | [default to undefined]

## Example

```typescript
import { MessageReactionCountUpdated } from 'tele_rest';

const instance: MessageReactionCountUpdated = {
    chat,
    message_id,
    date,
    reactions,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
