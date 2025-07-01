# PassportElementErrorFrontSide

Represents an issue with the front side of a document. The error is considered resolved when the file with the front side of the document changes.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **string** | Error source, must be *front\\_side* | [default to 'front_side']
**type** | **string** | The section of the user\&#39;s Telegram Passport which has the issue, one of “passport”, “driver\\_license”, “identity\\_card”, “internal\\_passport” | [default to undefined]
**file_hash** | **string** | Base64-encoded hash of the file with the front side of the document | [default to undefined]
**message** | **string** | Error message | [default to undefined]

## Example

```typescript
import { PassportElementErrorFrontSide } from 'tele_rest';

const instance: PassportElementErrorFrontSide = {
    source,
    type,
    file_hash,
    message,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
