# StoryAreaTypeSuggestedReaction

Describes a story area pointing to a suggested reaction. Currently, a story can have up to 5 suggested reaction areas.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the area, always “suggested\\_reaction” | [default to 'suggested_reaction']
**reaction_type** | [**ReactionType**](ReactionType.md) |  | [default to undefined]
**is_dark** | **boolean** | *Optional*. Pass *True* if the reaction area has a dark background | [optional] [default to undefined]
**is_flipped** | **boolean** | *Optional*. Pass *True* if reaction area corner is flipped | [optional] [default to undefined]

## Example

```typescript
import { StoryAreaTypeSuggestedReaction } from 'tele_rest';

const instance: StoryAreaTypeSuggestedReaction = {
    type,
    reaction_type,
    is_dark,
    is_flipped,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
