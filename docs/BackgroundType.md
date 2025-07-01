# BackgroundType

This object describes the type of a background. Currently, it can be one of  * [BackgroundTypeFill](https://core.telegram.org/bots/api/#backgroundtypefill) * [BackgroundTypeWallpaper](https://core.telegram.org/bots/api/#backgroundtypewallpaper) * [BackgroundTypePattern](https://core.telegram.org/bots/api/#backgroundtypepattern) * [BackgroundTypeChatTheme](https://core.telegram.org/bots/api/#backgroundtypechattheme)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the background, always “chat\\_theme” | [default to 'chat_theme']
**fill** | [**BackgroundFill**](BackgroundFill.md) |  | [default to undefined]
**dark_theme_dimming** | **number** | Dimming of the background in dark themes, as a percentage; 0-100 | [default to undefined]
**document** | [**Document**](Document.md) |  | [default to undefined]
**intensity** | **number** | Intensity of the pattern when it is shown above the filled background; 0-100 | [default to undefined]
**theme_name** | **string** | Name of the chat theme, which is usually an emoji | [default to undefined]
**is_blurred** | **boolean** | *Optional*. *True*, if the wallpaper is downscaled to fit in a 450x450 square and then box-blurred with radius 12 | [optional] [default to true]
**is_moving** | **boolean** | *Optional*. *True*, if the background moves slightly when the device is tilted | [optional] [default to true]
**is_inverted** | **boolean** | *Optional*. *True*, if the background fill must be applied only to the pattern itself. All other pixels are black in this case. For dark themes only | [optional] [default to true]

## Example

```typescript
import { BackgroundType } from 'tele_rest';

const instance: BackgroundType = {
    type,
    fill,
    dark_theme_dimming,
    document,
    intensity,
    theme_name,
    is_blurred,
    is_moving,
    is_inverted,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
