# SetBusinessAccountProfilePhotoRequest

Request parameters for setBusinessAccountProfilePhoto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection | [default to undefined]
**photo** | [**InputProfilePhoto**](InputProfilePhoto.md) |  | [default to undefined]
**is_public** | **boolean** | Pass True to set the public photo, which will be visible even if the main photo is hidden by the business account\&#39;s privacy settings. An account can have only one public photo. | [optional] [default to undefined]

## Example

```typescript
import { SetBusinessAccountProfilePhotoRequest } from 'tele_rest';

const instance: SetBusinessAccountProfilePhotoRequest = {
    business_connection_id,
    photo,
    is_public,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
