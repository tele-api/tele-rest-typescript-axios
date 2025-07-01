# BackgroundTypeFill

The background is automatically filled based on the selected colors.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the background, always “fill” | [default to 'fill']
**fill** | [**BackgroundFill**](BackgroundFill.md) |  | [default to undefined]
**dark_theme_dimming** | **number** | Dimming of the background in dark themes, as a percentage; 0-100 | [default to undefined]

## Example

```typescript
import { BackgroundTypeFill } from 'tele_rest';

const instance: BackgroundTypeFill = {
    type,
    fill,
    dark_theme_dimming,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
