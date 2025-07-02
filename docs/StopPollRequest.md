# StopPollRequest

Request parameters for stopPoll

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**SendMessageRequestChatId**](SendMessageRequestChatId.md) |  | [default to undefined]
**message_id** | **number** | Identifier of the original message with the poll | [default to undefined]
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which the message to be edited was sent | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]

## Example

```typescript
import { StopPollRequest } from 'tele_rest';

const instance: StopPollRequest = {
    chat_id,
    message_id,
    business_connection_id,
    reply_markup,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
