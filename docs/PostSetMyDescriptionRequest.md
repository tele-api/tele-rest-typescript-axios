# PostSetMyDescriptionRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **string** | New bot description; 0-512 characters. Pass an empty string to remove the dedicated description for the given language. | [optional] [default to undefined]
**language_code** | **string** | A two-letter ISO 639-1 language code. If empty, the description will be applied to all users for whose language there is no dedicated description. | [optional] [default to undefined]

## Example

```typescript
import { PostSetMyDescriptionRequest } from 'tele_rest';

const instance: PostSetMyDescriptionRequest = {
    description,
    language_code,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
