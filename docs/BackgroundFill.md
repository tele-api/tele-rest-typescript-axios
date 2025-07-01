# BackgroundFill

This object describes the way a background is filled based on the selected colors. Currently, it can be one of  * [BackgroundFillSolid](https://core.telegram.org/bots/api/#backgroundfillsolid) * [BackgroundFillGradient](https://core.telegram.org/bots/api/#backgroundfillgradient) * [BackgroundFillFreeformGradient](https://core.telegram.org/bots/api/#backgroundfillfreeformgradient)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the background fill, always “freeform\\_gradient” | [default to 'freeform_gradient']
**color** | **number** | The color of the background fill in the RGB24 format | [default to undefined]
**top_color** | **number** | Top color of the gradient in the RGB24 format | [default to undefined]
**bottom_color** | **number** | Bottom color of the gradient in the RGB24 format | [default to undefined]
**rotation_angle** | **number** | Clockwise rotation angle of the background fill in degrees; 0-359 | [default to undefined]
**colors** | **Array&lt;number&gt;** | A list of the 3 or 4 base colors that are used to generate the freeform gradient in the RGB24 format | [default to undefined]

## Example

```typescript
import { BackgroundFill } from 'tele_rest';

const instance: BackgroundFill = {
    type,
    color,
    top_color,
    bottom_color,
    rotation_angle,
    colors,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
