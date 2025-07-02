# SetStickerEmojiListRequest

Request parameters for setStickerEmojiList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sticker** | **string** | File identifier of the sticker | [default to undefined]
**emoji_list** | **Array&lt;string&gt;** | A JSON-serialized list of 1-20 emoji associated with the sticker | [default to undefined]

## Example

```typescript
import { SetStickerEmojiListRequest } from 'tele_rest';

const instance: SetStickerEmojiListRequest = {
    sticker,
    emoji_list,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
