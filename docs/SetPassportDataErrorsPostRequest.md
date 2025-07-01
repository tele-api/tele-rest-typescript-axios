# SetPassportDataErrorsPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **number** | User identifier | [default to undefined]
**errors** | [**Array&lt;PassportElementError&gt;**](PassportElementError.md) | A JSON-serialized array describing the errors | [default to undefined]

## Example

```typescript
import { SetPassportDataErrorsPostRequest } from 'tele_rest';

const instance: SetPassportDataErrorsPostRequest = {
    user_id,
    errors,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
