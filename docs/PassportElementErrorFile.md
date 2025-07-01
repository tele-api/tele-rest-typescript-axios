# PassportElementErrorFile

Represents an issue with a document scan. The error is considered resolved when the file with the document scan changes.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **string** | Error source, must be *file* | [default to 'file']
**type** | **string** | The section of the user\&#39;s Telegram Passport which has the issue, one of “utility\\_bill”, “bank\\_statement”, “rental\\_agreement”, “passport\\_registration”, “temporary\\_registration” | [default to undefined]
**file_hash** | **string** | Base64-encoded file hash | [default to undefined]
**message** | **string** | Error message | [default to undefined]

## Example

```typescript
import { PassportElementErrorFile } from 'tele_rest';

const instance: PassportElementErrorFile = {
    source,
    type,
    file_hash,
    message,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
