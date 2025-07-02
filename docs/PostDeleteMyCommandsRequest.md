# PostDeleteMyCommandsRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**scope** | [**BotCommandScope**](BotCommandScope.md) |  | [optional] [default to undefined]
**language_code** | **string** | A two-letter ISO 639-1 language code. If empty, commands will be applied to all users from the given scope, for whose language there are no dedicated commands | [optional] [default to undefined]

## Example

```typescript
import { PostDeleteMyCommandsRequest } from 'tele_rest';

const instance: PostDeleteMyCommandsRequest = {
    scope,
    language_code,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
