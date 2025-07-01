# PassportElementErrorFiles

Represents an issue with a list of scans. The error is considered resolved when the list of files containing the scans changes.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **string** | Error source, must be *files* | [default to 'files']
**type** | **string** | The section of the user\&#39;s Telegram Passport which has the issue, one of “utility\\_bill”, “bank\\_statement”, “rental\\_agreement”, “passport\\_registration”, “temporary\\_registration” | [default to undefined]
**file_hashes** | **Array&lt;string&gt;** | List of base64-encoded file hashes | [default to undefined]
**message** | **string** | Error message | [default to undefined]

## Example

```typescript
import { PassportElementErrorFiles } from 'tele_rest';

const instance: PassportElementErrorFiles = {
    source,
    type,
    file_hashes,
    message,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
