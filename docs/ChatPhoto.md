# ChatPhoto

This object represents a chat photo.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**small_file_id** | **string** | File identifier of small (160x160) chat photo. This file\\_id can be used only for photo download and only for as long as the photo is not changed. | [default to undefined]
**small_file_unique_id** | **string** | Unique file identifier of small (160x160) chat photo, which is supposed to be the same over time and for different bots. Can\&#39;t be used to download or reuse the file. | [default to undefined]
**big_file_id** | **string** | File identifier of big (640x640) chat photo. This file\\_id can be used only for photo download and only for as long as the photo is not changed. | [default to undefined]
**big_file_unique_id** | **string** | Unique file identifier of big (640x640) chat photo, which is supposed to be the same over time and for different bots. Can\&#39;t be used to download or reuse the file. | [default to undefined]

## Example

```typescript
import { ChatPhoto } from 'tele_rest';

const instance: ChatPhoto = {
    small_file_id,
    small_file_unique_id,
    big_file_id,
    big_file_unique_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
