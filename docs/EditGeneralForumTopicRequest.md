# EditGeneralForumTopicRequest

Request parameters for editGeneralForumTopic

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**BotCommandScopeChatChatId**](BotCommandScopeChatChatId.md) |  | [default to undefined]
**name** | **string** | New topic name, 1-128 characters | [default to undefined]

## Example

```typescript
import { EditGeneralForumTopicRequest } from 'tele_rest';

const instance: EditGeneralForumTopicRequest = {
    chat_id,
    name,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
