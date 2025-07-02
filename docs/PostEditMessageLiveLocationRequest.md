# PostEditMessageLiveLocationRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**latitude** | **number** | Latitude of new location | [default to undefined]
**longitude** | **number** | Longitude of new location | [default to undefined]
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which the message to be edited was sent | [optional] [default to undefined]
**chat_id** | [**PostEditMessageTextRequestChatId**](PostEditMessageTextRequestChatId.md) |  | [optional] [default to undefined]
**message_id** | **number** | Required if *inline\\_message\\_id* is not specified. Identifier of the message to edit | [optional] [default to undefined]
**inline_message_id** | **string** | Required if *chat\\_id* and *message\\_id* are not specified. Identifier of the inline message | [optional] [default to undefined]
**live_period** | **number** | New period in seconds during which the location can be updated, starting from the message send date. If 0x7FFFFFFF is specified, then the location can be updated forever. Otherwise, the new value must not exceed the current *live\\_period* by more than a day, and the live location expiration date must remain within the next 90 days. If not specified, then *live\\_period* remains unchanged | [optional] [default to undefined]
**horizontal_accuracy** | **number** | The radius of uncertainty for the location, measured in meters; 0-1500 | [optional] [default to undefined]
**heading** | **number** | Direction in which the user is moving, in degrees. Must be between 1 and 360 if specified. | [optional] [default to undefined]
**proximity_alert_radius** | **number** | The maximum distance for proximity alerts about approaching another chat member, in meters. Must be between 1 and 100000 if specified. | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]

## Example

```typescript
import { PostEditMessageLiveLocationRequest } from 'tele_rest';

const instance: PostEditMessageLiveLocationRequest = {
    latitude,
    longitude,
    business_connection_id,
    chat_id,
    message_id,
    inline_message_id,
    live_period,
    horizontal_accuracy,
    heading,
    proximity_alert_radius,
    reply_markup,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
