# StoryAreaTypeWeather

Describes a story area containing weather information. Currently, a story can have up to 3 weather areas.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the area, always “weather” | [default to 'weather']
**temperature** | **number** | Temperature, in degree Celsius | [default to undefined]
**emoji** | **string** | Emoji representing the weather | [default to undefined]
**background_color** | **number** | A color of the area background in the ARGB format | [default to undefined]

## Example

```typescript
import { StoryAreaTypeWeather } from 'tele_rest';

const instance: StoryAreaTypeWeather = {
    type,
    temperature,
    emoji,
    background_color,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
