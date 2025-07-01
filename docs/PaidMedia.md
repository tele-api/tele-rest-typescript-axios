# PaidMedia

This object describes paid media. Currently, it can be one of  * [PaidMediaPreview](https://core.telegram.org/bots/api/#paidmediapreview) * [PaidMediaPhoto](https://core.telegram.org/bots/api/#paidmediaphoto) * [PaidMediaVideo](https://core.telegram.org/bots/api/#paidmediavideo)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the paid media, always “video” | [default to 'video']
**photo** | [**Array&lt;PhotoSize&gt;**](PhotoSize.md) | The photo | [default to undefined]
**video** | [**Video**](Video.md) |  | [default to undefined]
**width** | **number** | *Optional*. Media width as defined by the sender | [optional] [default to undefined]
**height** | **number** | *Optional*. Media height as defined by the sender | [optional] [default to undefined]
**duration** | **number** | *Optional*. Duration of the media in seconds as defined by the sender | [optional] [default to undefined]

## Example

```typescript
import { PaidMedia } from 'tele_rest';

const instance: PaidMedia = {
    type,
    photo,
    video,
    width,
    height,
    duration,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
