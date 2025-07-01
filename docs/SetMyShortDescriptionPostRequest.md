# SetMyShortDescriptionPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**short_description** | **string** | New short description for the bot; 0-120 characters. Pass an empty string to remove the dedicated short description for the given language. | [optional] [default to undefined]
**language_code** | **string** | A two-letter ISO 639-1 language code. If empty, the short description will be applied to all users for whose language there is no dedicated short description. | [optional] [default to undefined]

## Example

```typescript
import { SetMyShortDescriptionPostRequest } from 'tele_rest';

const instance: SetMyShortDescriptionPostRequest = {
    short_description,
    language_code,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
