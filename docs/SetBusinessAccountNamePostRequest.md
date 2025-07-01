# SetBusinessAccountNamePostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection | [default to undefined]
**first_name** | **string** | The new value of the first name for the business account; 1-64 characters | [default to undefined]
**last_name** | **string** | The new value of the last name for the business account; 0-64 characters | [optional] [default to undefined]

## Example

```typescript
import { SetBusinessAccountNamePostRequest } from 'tele_rest';

const instance: SetBusinessAccountNamePostRequest = {
    business_connection_id,
    first_name,
    last_name,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
