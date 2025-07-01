# StoryAreaTypeLink

Describes a story area pointing to an HTTP or tg:// link. Currently, a story can have up to 3 link areas.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the area, always “link” | [default to 'link']
**url** | **string** | HTTP or tg:// URL to be opened when the area is clicked | [default to undefined]

## Example

```typescript
import { StoryAreaTypeLink } from 'tele_rest';

const instance: StoryAreaTypeLink = {
    type,
    url,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
