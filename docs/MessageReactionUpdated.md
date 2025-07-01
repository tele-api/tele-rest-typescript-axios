# MessageReactionUpdated

This object represents a change of a reaction on a message performed by a user.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat** | [**Chat**](Chat.md) |  | [default to undefined]
**message_id** | **number** | Unique identifier of the message inside the chat | [default to undefined]
**date** | **number** | Date of the change in Unix time | [default to undefined]
**old_reaction** | [**Array&lt;ReactionType&gt;**](ReactionType.md) | Previous list of reaction types that were set by the user | [default to undefined]
**new_reaction** | [**Array&lt;ReactionType&gt;**](ReactionType.md) | New list of reaction types that have been set by the user | [default to undefined]
**user** | [**User**](User.md) |  | [optional] [default to undefined]
**actor_chat** | [**Chat**](Chat.md) |  | [optional] [default to undefined]

## Example

```typescript
import { MessageReactionUpdated } from 'tele_rest';

const instance: MessageReactionUpdated = {
    chat,
    message_id,
    date,
    old_reaction,
    new_reaction,
    user,
    actor_chat,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
