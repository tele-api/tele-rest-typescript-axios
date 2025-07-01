# InputProfilePhotoAnimated

An animated profile photo in the MPEG4 format.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the profile photo, must be *animated* | [default to 'animated']
**animation** | **string** | The animated profile photo. Profile photos can\&#39;t be reused and can only be uploaded as a new file, so you can pass “attach://\\&lt;file\\_attach\\_name\\&gt;” if the photo was uploaded using multipart/form-data under \\&lt;file\\_attach\\_name\\&gt;. [More information on Sending Files »](https://core.telegram.org/bots/api/#sending-files) | [default to undefined]
**main_frame_timestamp** | **number** | *Optional*. Timestamp in seconds of the frame that will be used as the static profile photo. Defaults to 0.0. | [optional] [default to undefined]

## Example

```typescript
import { InputProfilePhotoAnimated } from 'tele_rest';

const instance: InputProfilePhotoAnimated = {
    type,
    animation,
    main_frame_timestamp,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
