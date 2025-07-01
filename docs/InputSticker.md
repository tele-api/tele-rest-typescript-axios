# InputSticker

This object describes a sticker to be added to a sticker set.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sticker** | **string** | The added sticker. Pass a *file\\_id* as a String to send a file that already exists on the Telegram servers, pass an HTTP URL as a String for Telegram to get a file from the Internet, or pass “attach://\\&lt;file\\_attach\\_name\\&gt;” to upload a new file using multipart/form-data under \\&lt;file\\_attach\\_name\\&gt; name. Animated and video stickers can\&#39;t be uploaded via HTTP URL. [More information on Sending Files »](https://core.telegram.org/bots/api/#sending-files) | [default to undefined]
**format** | **string** | Format of the added sticker, must be one of “static” for a **.WEBP** or **.PNG** image, “animated” for a **.TGS** animation, “video” for a **.WEBM** video | [default to undefined]
**emoji_list** | **Array&lt;string&gt;** | List of 1-20 emoji associated with the sticker | [default to undefined]
**mask_position** | [**MaskPosition**](MaskPosition.md) |  | [optional] [default to undefined]
**keywords** | **Array&lt;string&gt;** | *Optional*. List of 0-20 search keywords for the sticker with total length of up to 64 characters. For “regular” and “custom\\_emoji” stickers only. | [optional] [default to undefined]

## Example

```typescript
import { InputSticker } from 'tele_rest';

const instance: InputSticker = {
    sticker,
    format,
    emoji_list,
    mask_position,
    keywords,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
