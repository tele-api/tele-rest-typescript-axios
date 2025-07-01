# PassportElementErrorUnspecified

Represents an issue in an unspecified place. The error is considered resolved when new data is added.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **string** | Error source, must be *unspecified* | [default to 'unspecified']
**type** | **string** | Type of element of the user\&#39;s Telegram Passport which has the issue | [default to undefined]
**element_hash** | **string** | Base64-encoded element hash | [default to undefined]
**message** | **string** | Error message | [default to undefined]

## Example

```typescript
import { PassportElementErrorUnspecified } from 'tele_rest';

const instance: PassportElementErrorUnspecified = {
    source,
    type,
    element_hash,
    message,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
