# PhotoSize

This object represents one size of a photo or a [file](https://core.telegram.org/bots/api/#document) / [sticker](https://core.telegram.org/bots/api/#sticker) thumbnail.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_id** | **string** | Identifier for this file, which can be used to download or reuse the file | [default to undefined]
**file_unique_id** | **string** | Unique identifier for this file, which is supposed to be the same over time and for different bots. Can\&#39;t be used to download or reuse the file. | [default to undefined]
**width** | **number** | Photo width | [default to undefined]
**height** | **number** | Photo height | [default to undefined]
**file_size** | **number** | *Optional*. File size in bytes | [optional] [default to undefined]

## Example

```typescript
import { PhotoSize } from 'tele_rest';

const instance: PhotoSize = {
    file_id,
    file_unique_id,
    width,
    height,
    file_size,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
