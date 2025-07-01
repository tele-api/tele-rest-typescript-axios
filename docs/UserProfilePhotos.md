# UserProfilePhotos

This object represent a user\'s profile pictures.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_count** | **number** | Total number of profile pictures the target user has | [default to undefined]
**photos** | **Array&lt;Array&lt;PhotoSize&gt;&gt;** | Requested profile pictures (in up to 4 sizes each) | [default to undefined]

## Example

```typescript
import { UserProfilePhotos } from 'tele_rest';

const instance: UserProfilePhotos = {
    total_count,
    photos,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
