# InputProfilePhotoStatic

A static profile photo in the .JPG format.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the profile photo, must be *static* | [default to 'static']
**photo** | **string** | The static profile photo. Profile photos can\&#39;t be reused and can only be uploaded as a new file, so you can pass “attach://\\&lt;file\\_attach\\_name\\&gt;” if the photo was uploaded using multipart/form-data under \\&lt;file\\_attach\\_name\\&gt;. [More information on Sending Files »](https://core.telegram.org/bots/api/#sending-files) | [default to undefined]

## Example

```typescript
import { InputProfilePhotoStatic } from 'tele_rest';

const instance: InputProfilePhotoStatic = {
    type,
    photo,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
