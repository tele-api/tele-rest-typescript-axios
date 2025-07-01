# PassportElementErrorReverseSide

Represents an issue with the reverse side of a document. The error is considered resolved when the file with reverse side of the document changes.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **string** | Error source, must be *reverse\\_side* | [default to 'reverse_side']
**type** | **string** | The section of the user\&#39;s Telegram Passport which has the issue, one of “driver\\_license”, “identity\\_card” | [default to undefined]
**file_hash** | **string** | Base64-encoded hash of the file with the reverse side of the document | [default to undefined]
**message** | **string** | Error message | [default to undefined]

## Example

```typescript
import { PassportElementErrorReverseSide } from 'tele_rest';

const instance: PassportElementErrorReverseSide = {
    source,
    type,
    file_hash,
    message,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
