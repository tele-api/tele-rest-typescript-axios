# PassportElementErrorDataField

Represents an issue in one of the data fields that was provided by the user. The error is considered resolved when the field\'s value changes.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **string** | Error source, must be *data* | [default to 'data']
**type** | **string** | The section of the user\&#39;s Telegram Passport which has the error, one of “personal\\_details”, “passport”, “driver\\_license”, “identity\\_card”, “internal\\_passport”, “address” | [default to undefined]
**field_name** | **string** | Name of the data field which has the error | [default to undefined]
**data_hash** | **string** | Base64-encoded data hash | [default to undefined]
**message** | **string** | Error message | [default to undefined]

## Example

```typescript
import { PassportElementErrorDataField } from 'tele_rest';

const instance: PassportElementErrorDataField = {
    source,
    type,
    field_name,
    data_hash,
    message,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
