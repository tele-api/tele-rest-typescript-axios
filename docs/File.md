# ModelFile

This object represents a file ready to be downloaded. The file can be downloaded via the link `https://api.telegram.org/file/bot<token>/<file_path>`. It is guaranteed that the link will be valid for at least 1 hour. When the link expires, a new one can be requested by calling [getFile](https://core.telegram.org/bots/api/#getfile).  The maximum file size to download is 20 MB

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_id** | **string** | Identifier for this file, which can be used to download or reuse the file | [default to undefined]
**file_unique_id** | **string** | Unique identifier for this file, which is supposed to be the same over time and for different bots. Can\&#39;t be used to download or reuse the file. | [default to undefined]
**file_size** | **number** | *Optional*. File size in bytes. It can be bigger than 2^31 and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a signed 64-bit integer or double-precision float type are safe for storing this value. | [optional] [default to undefined]
**file_path** | **string** | *Optional*. File path. Use &#x60;https://api.telegram.org/file/bot&lt;token&gt;/&lt;file_path&gt;&#x60; to get the file. | [optional] [default to undefined]

## Example

```typescript
import { ModelFile } from 'tele_rest';

const instance: ModelFile = {
    file_id,
    file_unique_id,
    file_size,
    file_path,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
