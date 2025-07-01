# BackgroundTypePattern

The background is a .PNG or .TGV (gzipped subset of SVG with MIME type “application/x-tgwallpattern”) pattern to be combined with the background fill chosen by the user.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the background, always “pattern” | [default to 'pattern']
**document** | [**Document**](Document.md) |  | [default to undefined]
**fill** | [**BackgroundFill**](BackgroundFill.md) |  | [default to undefined]
**intensity** | **number** | Intensity of the pattern when it is shown above the filled background; 0-100 | [default to undefined]
**is_inverted** | **boolean** | *Optional*. *True*, if the background fill must be applied only to the pattern itself. All other pixels are black in this case. For dark themes only | [optional] [default to true]
**is_moving** | **boolean** | *Optional*. *True*, if the background moves slightly when the device is tilted | [optional] [default to true]

## Example

```typescript
import { BackgroundTypePattern } from 'tele_rest';

const instance: BackgroundTypePattern = {
    type,
    document,
    fill,
    intensity,
    is_inverted,
    is_moving,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
