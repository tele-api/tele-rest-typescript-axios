# PaidMediaPreview

The paid media isn\'t available before the payment.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the paid media, always “preview” | [default to 'preview']
**width** | **number** | *Optional*. Media width as defined by the sender | [optional] [default to undefined]
**height** | **number** | *Optional*. Media height as defined by the sender | [optional] [default to undefined]
**duration** | **number** | *Optional*. Duration of the media in seconds as defined by the sender | [optional] [default to undefined]

## Example

```typescript
import { PaidMediaPreview } from 'tele_rest';

const instance: PaidMediaPreview = {
    type,
    width,
    height,
    duration,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
