# PollOption

This object contains information about one answer option in a poll.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **string** | Option text, 1-100 characters | [default to undefined]
**voter_count** | **number** | Number of users that voted for this option | [default to undefined]
**text_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. Special entities that appear in the option *text*. Currently, only custom emoji entities are allowed in poll option texts | [optional] [default to undefined]

## Example

```typescript
import { PollOption } from 'tele_rest';

const instance: PollOption = {
    text,
    voter_count,
    text_entities,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
