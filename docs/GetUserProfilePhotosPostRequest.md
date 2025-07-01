# GetUserProfilePhotosPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **number** | Unique identifier of the target user | [default to undefined]
**offset** | **number** | Sequential number of the first photo to be returned. By default, all photos are returned. | [optional] [default to undefined]
**limit** | **number** | Limits the number of photos to be retrieved. Values between 1-100 are accepted. Defaults to 100. | [optional] [default to 100]

## Example

```typescript
import { GetUserProfilePhotosPostRequest } from 'tele_rest';

const instance: GetUserProfilePhotosPostRequest = {
    user_id,
    offset,
    limit,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
