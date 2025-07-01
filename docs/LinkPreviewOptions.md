# LinkPreviewOptions

Describes the options used for link preview generation.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**is_disabled** | **boolean** | *Optional*. *True*, if the link preview is disabled | [optional] [default to undefined]
**url** | **string** | *Optional*. URL to use for the link preview. If empty, then the first URL found in the message text will be used | [optional] [default to undefined]
**prefer_small_media** | **boolean** | *Optional*. *True*, if the media in the link preview is supposed to be shrunk; ignored if the URL isn\&#39;t explicitly specified or media size change isn\&#39;t supported for the preview | [optional] [default to undefined]
**prefer_large_media** | **boolean** | *Optional*. *True*, if the media in the link preview is supposed to be enlarged; ignored if the URL isn\&#39;t explicitly specified or media size change isn\&#39;t supported for the preview | [optional] [default to undefined]
**show_above_text** | **boolean** | *Optional*. *True*, if the link preview must be shown above the message text; otherwise, the link preview will be shown below the message text | [optional] [default to undefined]

## Example

```typescript
import { LinkPreviewOptions } from 'tele_rest';

const instance: LinkPreviewOptions = {
    is_disabled,
    url,
    prefer_small_media,
    prefer_large_media,
    show_above_text,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
