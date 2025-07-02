# PostSetMyNameRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | New bot name; 0-64 characters. Pass an empty string to remove the dedicated name for the given language. | [optional] [default to undefined]
**language_code** | **string** | A two-letter ISO 639-1 language code. If empty, the name will be shown to all users for whose language there is no dedicated name. | [optional] [default to undefined]

## Example

```typescript
import { PostSetMyNameRequest } from 'tele_rest';

const instance: PostSetMyNameRequest = {
    name,
    language_code,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
