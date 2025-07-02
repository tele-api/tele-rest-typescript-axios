# SetChatMenuButtonRequest

Request parameters for setChatMenuButton

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | **number** | Unique identifier for the target private chat. If not specified, default bot\&#39;s menu button will be changed | [optional] [default to undefined]
**menu_button** | [**MenuButton**](MenuButton.md) |  | [optional] [default to undefined]

## Example

```typescript
import { SetChatMenuButtonRequest } from 'tele_rest';

const instance: SetChatMenuButtonRequest = {
    chat_id,
    menu_button,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
