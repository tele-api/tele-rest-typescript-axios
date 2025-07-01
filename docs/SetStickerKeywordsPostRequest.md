# SetStickerKeywordsPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sticker** | **string** | File identifier of the sticker | [default to undefined]
**keywords** | **Array&lt;string&gt;** | A JSON-serialized list of 0-20 search keywords for the sticker with total length of up to 64 characters | [optional] [default to undefined]

## Example

```typescript
import { SetStickerKeywordsPostRequest } from 'tele_rest';

const instance: SetStickerKeywordsPostRequest = {
    sticker,
    keywords,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
