# CreateForumTopicRequest

Request parameters for createForumTopic

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**BotCommandScopeChatChatId**](BotCommandScopeChatChatId.md) |  | [default to undefined]
**name** | **string** | Topic name, 1-128 characters | [default to undefined]
**icon_color** | **number** | Color of the topic icon in RGB format. Currently, must be one of 7322096 (0x6FB9F0), 16766590 (0xFFD67E), 13338331 (0xCB86DB), 9367192 (0x8EEE98), 16749490 (0xFF93B2), or 16478047 (0xFB6F5F) | [optional] [default to undefined]
**icon_custom_emoji_id** | **string** | Unique identifier of the custom emoji shown as the topic icon. Use [getForumTopicIconStickers](https://core.telegram.org/bots/api/#getforumtopiciconstickers) to get all allowed custom emoji identifiers. | [optional] [default to undefined]

## Example

```typescript
import { CreateForumTopicRequest } from 'tele_rest';

const instance: CreateForumTopicRequest = {
    chat_id,
    name,
    icon_color,
    icon_custom_emoji_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
