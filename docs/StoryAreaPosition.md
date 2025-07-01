# StoryAreaPosition

Describes the position of a clickable area within a story.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**x_percentage** | **number** | The abscissa of the area\&#39;s center, as a percentage of the media width | [default to undefined]
**y_percentage** | **number** | The ordinate of the area\&#39;s center, as a percentage of the media height | [default to undefined]
**width_percentage** | **number** | The width of the area\&#39;s rectangle, as a percentage of the media width | [default to undefined]
**height_percentage** | **number** | The height of the area\&#39;s rectangle, as a percentage of the media height | [default to undefined]
**rotation_angle** | **number** | The clockwise rotation angle of the rectangle, in degrees; 0-360 | [default to undefined]
**corner_radius_percentage** | **number** | The radius of the rectangle corner rounding, as a percentage of the media width | [default to undefined]

## Example

```typescript
import { StoryAreaPosition } from 'tele_rest';

const instance: StoryAreaPosition = {
    x_percentage,
    y_percentage,
    width_percentage,
    height_percentage,
    rotation_angle,
    corner_radius_percentage,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
