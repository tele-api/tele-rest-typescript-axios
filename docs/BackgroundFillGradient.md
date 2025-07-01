# BackgroundFillGradient

The background is a gradient fill.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the background fill, always “gradient” | [default to 'gradient']
**top_color** | **number** | Top color of the gradient in the RGB24 format | [default to undefined]
**bottom_color** | **number** | Bottom color of the gradient in the RGB24 format | [default to undefined]
**rotation_angle** | **number** | Clockwise rotation angle of the background fill in degrees; 0-359 | [default to undefined]

## Example

```typescript
import { BackgroundFillGradient } from 'tele_rest';

const instance: BackgroundFillGradient = {
    type,
    top_color,
    bottom_color,
    rotation_angle,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
