# SetChatStickerSetRequest

Request parameters for setChatStickerSet

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**BotCommandScopeChatChatId**](BotCommandScopeChatChatId.md) |  | [default to undefined]
**sticker_set_name** | **string** | Name of the sticker set to be set as the group sticker set | [default to undefined]

## Example

```typescript
import { SetChatStickerSetRequest } from 'tele_rest';

const instance: SetChatStickerSetRequest = {
    chat_id,
    sticker_set_name,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
