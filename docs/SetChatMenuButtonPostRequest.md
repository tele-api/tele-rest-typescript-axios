# SetChatMenuButtonPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | **number** | Unique identifier for the target private chat. If not specified, default bot\&#39;s menu button will be changed | [optional] [default to undefined]
**menu_button** | [**MenuButton**](MenuButton.md) |  | [optional] [default to undefined]

## Example

```typescript
import { SetChatMenuButtonPostRequest } from 'tele_rest';

const instance: SetChatMenuButtonPostRequest = {
    chat_id,
    menu_button,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
