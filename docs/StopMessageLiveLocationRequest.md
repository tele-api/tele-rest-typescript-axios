# StopMessageLiveLocationRequest

Request parameters for stopMessageLiveLocation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which the message to be edited was sent | [optional] [default to undefined]
**chat_id** | [**EditMessageTextRequestChatId**](EditMessageTextRequestChatId.md) |  | [optional] [default to undefined]
**message_id** | **number** | Required if *inline\\_message\\_id* is not specified. Identifier of the message with live location to stop | [optional] [default to undefined]
**inline_message_id** | **string** | Required if *chat\\_id* and *message\\_id* are not specified. Identifier of the inline message | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]

## Example

```typescript
import { StopMessageLiveLocationRequest } from 'tele_rest';

const instance: StopMessageLiveLocationRequest = {
    business_connection_id,
    chat_id,
    message_id,
    inline_message_id,
    reply_markup,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
