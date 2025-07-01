# InaccessibleMessage

This object describes a message that was deleted or is otherwise inaccessible to the bot.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat** | [**Chat**](Chat.md) |  | [default to undefined]
**message_id** | **number** | Unique message identifier inside the chat | [default to undefined]
**date** | **number** | Always 0. The field can be used to differentiate regular and inaccessible messages. | [default to undefined]

## Example

```typescript
import { InaccessibleMessage } from 'tele_rest';

const instance: InaccessibleMessage = {
    chat,
    message_id,
    date,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
