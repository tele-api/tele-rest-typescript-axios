# ChosenInlineResult

Represents a [result](https://core.telegram.org/bots/api/#inlinequeryresult) of an inline query that was chosen by the user and sent to their chat partner.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**result_id** | **string** | The unique identifier for the result that was chosen | [default to undefined]
**from** | [**User**](User.md) |  | [default to undefined]
**query** | **string** | The query that was used to obtain the result | [default to undefined]
**location** | [**Location**](Location.md) |  | [optional] [default to undefined]
**inline_message_id** | **string** | *Optional*. Identifier of the sent inline message. Available only if there is an [inline keyboard](https://core.telegram.org/bots/api/#inlinekeyboardmarkup) attached to the message. Will be also received in [callback queries](https://core.telegram.org/bots/api/#callbackquery) and can be used to [edit](https://core.telegram.org/bots/api/#updating-messages) the message. | [optional] [default to undefined]

## Example

```typescript
import { ChosenInlineResult } from 'tele_rest';

const instance: ChosenInlineResult = {
    result_id,
    from,
    query,
    location,
    inline_message_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
