# Sticker

This object represents a sticker.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_id** | **string** | Identifier for this file, which can be used to download or reuse the file | [default to undefined]
**file_unique_id** | **string** | Unique identifier for this file, which is supposed to be the same over time and for different bots. Can\&#39;t be used to download or reuse the file. | [default to undefined]
**type** | **string** | Type of the sticker, currently one of “regular”, “mask”, “custom\\_emoji”. The type of the sticker is independent from its format, which is determined by the fields *is\\_animated* and *is\\_video*. | [default to undefined]
**width** | **number** | Sticker width | [default to undefined]
**height** | **number** | Sticker height | [default to undefined]
**is_animated** | **boolean** | *True*, if the sticker is [animated](https://telegram.org/blog/animated-stickers) | [default to undefined]
**is_video** | **boolean** | *True*, if the sticker is a [video sticker](https://telegram.org/blog/video-stickers-better-reactions) | [default to undefined]
**thumbnail** | [**PhotoSize**](PhotoSize.md) |  | [optional] [default to undefined]
**emoji** | **string** | *Optional*. Emoji associated with the sticker | [optional] [default to undefined]
**set_name** | **string** | *Optional*. Name of the sticker set to which the sticker belongs | [optional] [default to undefined]
**premium_animation** | **any** |  | [optional] [default to undefined]
**mask_position** | [**MaskPosition**](MaskPosition.md) |  | [optional] [default to undefined]
**custom_emoji_id** | **string** | *Optional*. For custom emoji stickers, unique identifier of the custom emoji | [optional] [default to undefined]
**needs_repainting** | **boolean** | *Optional*. *True*, if the sticker must be repainted to a text color in messages, the color of the Telegram Premium badge in emoji status, white color on chat photos, or another appropriate color in other places | [optional] [default to true]
**file_size** | **number** | *Optional*. File size in bytes | [optional] [default to undefined]

## Example

```typescript
import { Sticker } from 'tele_rest';

const instance: Sticker = {
    file_id,
    file_unique_id,
    type,
    width,
    height,
    is_animated,
    is_video,
    thumbnail,
    emoji,
    set_name,
    premium_animation,
    mask_position,
    custom_emoji_id,
    needs_repainting,
    file_size,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
