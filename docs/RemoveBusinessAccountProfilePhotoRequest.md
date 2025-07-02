# RemoveBusinessAccountProfilePhotoRequest

Request parameters for removeBusinessAccountProfilePhoto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection | [default to undefined]
**is_public** | **boolean** | Pass True to remove the public photo, which is visible even if the main photo is hidden by the business account\&#39;s privacy settings. After the main photo is removed, the previous profile photo (if present) becomes the main photo. | [optional] [default to undefined]

## Example

```typescript
import { RemoveBusinessAccountProfilePhotoRequest } from 'tele_rest';

const instance: RemoveBusinessAccountProfilePhotoRequest = {
    business_connection_id,
    is_public,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
