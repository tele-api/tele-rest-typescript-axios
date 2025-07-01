# ReactionCount

Represents a reaction added to a message along with the number of times it was added.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | [**ReactionType**](ReactionType.md) |  | [default to undefined]
**total_count** | **number** | Number of times the reaction was added | [default to undefined]

## Example

```typescript
import { ReactionCount } from 'tele_rest';

const instance: ReactionCount = {
    type,
    total_count,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
