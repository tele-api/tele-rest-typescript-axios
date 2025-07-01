# InlineQueryResultLocation

Represents a location on a map. By default, the location will be sent by the user. Alternatively, you can use *input\\_message\\_content* to send a message with the specified content instead of the location.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *location* | [default to 'location']
**id** | **string** | Unique identifier for this result, 1-64 Bytes | [default to undefined]
**latitude** | **number** | Location latitude in degrees | [default to undefined]
**longitude** | **number** | Location longitude in degrees | [default to undefined]
**title** | **string** | Location title | [default to undefined]
**horizontal_accuracy** | **number** | *Optional*. The radius of uncertainty for the location, measured in meters; 0-1500 | [optional] [default to undefined]
**live_period** | **number** | *Optional*. Period in seconds during which the location can be updated, should be between 60 and 86400, or 0x7FFFFFFF for live locations that can be edited indefinitely. | [optional] [default to undefined]
**heading** | **number** | *Optional*. For live locations, a direction in which the user is moving, in degrees. Must be between 1 and 360 if specified. | [optional] [default to undefined]
**proximity_alert_radius** | **number** | *Optional*. For live locations, a maximum distance for proximity alerts about approaching another chat member, in meters. Must be between 1 and 100000 if specified. | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]
**input_message_content** | [**InputMessageContent**](InputMessageContent.md) |  | [optional] [default to undefined]
**thumbnail_url** | **string** | *Optional*. Url of the thumbnail for the result | [optional] [default to undefined]
**thumbnail_width** | **number** | *Optional*. Thumbnail width | [optional] [default to undefined]
**thumbnail_height** | **number** | *Optional*. Thumbnail height | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultLocation } from 'tele_rest';

const instance: InlineQueryResultLocation = {
    type,
    id,
    latitude,
    longitude,
    title,
    horizontal_accuracy,
    live_period,
    heading,
    proximity_alert_radius,
    reply_markup,
    input_message_content,
    thumbnail_url,
    thumbnail_width,
    thumbnail_height,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
