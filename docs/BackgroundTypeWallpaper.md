# BackgroundTypeWallpaper

The background is a wallpaper in the JPEG format.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the background, always “wallpaper” | [default to 'wallpaper']
**document** | [**Document**](Document.md) |  | [default to undefined]
**dark_theme_dimming** | **number** | Dimming of the background in dark themes, as a percentage; 0-100 | [default to undefined]
**is_blurred** | **boolean** | *Optional*. *True*, if the wallpaper is downscaled to fit in a 450x450 square and then box-blurred with radius 12 | [optional] [default to true]
**is_moving** | **boolean** | *Optional*. *True*, if the background moves slightly when the device is tilted | [optional] [default to true]

## Example

```typescript
import { BackgroundTypeWallpaper } from 'tele_rest';

const instance: BackgroundTypeWallpaper = {
    type,
    document,
    dark_theme_dimming,
    is_blurred,
    is_moving,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
