# InputStoryContentPhoto

Describes a photo to post as a story.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the content, must be *photo* | [default to 'photo']
**photo** | **string** | The photo to post as a story. The photo must be of the size 1080x1920 and must not exceed 10 MB. The photo can\&#39;t be reused and can only be uploaded as a new file, so you can pass “attach://\\&lt;file\\_attach\\_name\\&gt;” if the photo was uploaded using multipart/form-data under \\&lt;file\\_attach\\_name\\&gt;. [More information on Sending Files »](https://core.telegram.org/bots/api/#sending-files) | [default to undefined]

## Example

```typescript
import { InputStoryContentPhoto } from 'tele_rest';

const instance: InputStoryContentPhoto = {
    type,
    photo,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
