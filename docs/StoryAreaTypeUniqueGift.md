# StoryAreaTypeUniqueGift

Describes a story area pointing to a unique gift. Currently, a story can have at most 1 unique gift area.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the area, always “unique\\_gift” | [default to 'unique_gift']
**name** | **string** | Unique name of the gift | [default to undefined]

## Example

```typescript
import { StoryAreaTypeUniqueGift } from 'tele_rest';

const instance: StoryAreaTypeUniqueGift = {
    type,
    name,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
