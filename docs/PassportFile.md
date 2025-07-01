# PassportFile

This object represents a file uploaded to Telegram Passport. Currently all Telegram Passport files are in JPEG format when decrypted and don\'t exceed 10MB.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_id** | **string** | Identifier for this file, which can be used to download or reuse the file | [default to undefined]
**file_unique_id** | **string** | Unique identifier for this file, which is supposed to be the same over time and for different bots. Can\&#39;t be used to download or reuse the file. | [default to undefined]
**file_size** | **number** | File size in bytes | [default to undefined]
**file_date** | **number** | Unix time when the file was uploaded | [default to undefined]

## Example

```typescript
import { PassportFile } from 'tele_rest';

const instance: PassportFile = {
    file_id,
    file_unique_id,
    file_size,
    file_date,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
