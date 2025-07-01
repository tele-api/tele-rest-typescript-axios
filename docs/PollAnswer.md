# PollAnswer

This object represents an answer of a user in a non-anonymous poll.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**poll_id** | **string** | Unique poll identifier | [default to undefined]
**option_ids** | **Array&lt;number&gt;** | 0-based identifiers of chosen answer options. May be empty if the vote was retracted. | [default to undefined]
**voter_chat** | [**Chat**](Chat.md) |  | [optional] [default to undefined]
**user** | [**User**](User.md) |  | [optional] [default to undefined]

## Example

```typescript
import { PollAnswer } from 'tele_rest';

const instance: PollAnswer = {
    poll_id,
    option_ids,
    voter_chat,
    user,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
