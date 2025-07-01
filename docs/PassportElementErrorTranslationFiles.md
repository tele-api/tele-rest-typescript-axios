# PassportElementErrorTranslationFiles

Represents an issue with the translated version of a document. The error is considered resolved when a file with the document translation change.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **string** | Error source, must be *translation\\_files* | [default to 'translation_files']
**type** | **string** | Type of element of the user\&#39;s Telegram Passport which has the issue, one of “passport”, “driver\\_license”, “identity\\_card”, “internal\\_passport”, “utility\\_bill”, “bank\\_statement”, “rental\\_agreement”, “passport\\_registration”, “temporary\\_registration” | [default to undefined]
**file_hashes** | **Array&lt;string&gt;** | List of base64-encoded file hashes | [default to undefined]
**message** | **string** | Error message | [default to undefined]

## Example

```typescript
import { PassportElementErrorTranslationFiles } from 'tele_rest';

const instance: PassportElementErrorTranslationFiles = {
    source,
    type,
    file_hashes,
    message,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
