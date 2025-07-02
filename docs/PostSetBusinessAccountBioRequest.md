# PostSetBusinessAccountBioRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection | [default to undefined]
**bio** | **string** | The new value of the bio for the business account; 0-140 characters | [optional] [default to undefined]

## Example

```typescript
import { PostSetBusinessAccountBioRequest } from 'tele_rest';

const instance: PostSetBusinessAccountBioRequest = {
    business_connection_id,
    bio,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
