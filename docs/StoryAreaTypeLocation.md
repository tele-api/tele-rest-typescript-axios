# StoryAreaTypeLocation

Describes a story area pointing to a location. Currently, a story can have up to 10 location areas.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the area, always “location” | [default to 'location']
**latitude** | **number** | Location latitude in degrees | [default to undefined]
**longitude** | **number** | Location longitude in degrees | [default to undefined]
**address** | [**LocationAddress**](LocationAddress.md) |  | [optional] [default to undefined]

## Example

```typescript
import { StoryAreaTypeLocation } from 'tele_rest';

const instance: StoryAreaTypeLocation = {
    type,
    latitude,
    longitude,
    address,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
