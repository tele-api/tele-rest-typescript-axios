# InlineQueryResultVenue

Represents a venue. By default, the venue will be sent by the user. Alternatively, you can use *input\\_message\\_content* to send a message with the specified content instead of the venue.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *venue* | [default to 'venue']
**id** | **string** | Unique identifier for this result, 1-64 Bytes | [default to undefined]
**latitude** | **number** | Latitude of the venue location in degrees | [default to undefined]
**longitude** | **number** | Longitude of the venue location in degrees | [default to undefined]
**title** | **string** | Title of the venue | [default to undefined]
**address** | **string** | Address of the venue | [default to undefined]
**foursquare_id** | **string** | *Optional*. Foursquare identifier of the venue if known | [optional] [default to undefined]
**foursquare_type** | **string** | *Optional*. Foursquare type of the venue, if known. (For example, “arts\\_entertainment/default”, “arts\\_entertainment/aquarium” or “food/icecream”.) | [optional] [default to undefined]
**google_place_id** | **string** | *Optional*. Google Places identifier of the venue | [optional] [default to undefined]
**google_place_type** | **string** | *Optional*. Google Places type of the venue. (See [supported types](https://developers.google.com/places/web-service/supported_types).) | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]
**input_message_content** | [**InputMessageContent**](InputMessageContent.md) |  | [optional] [default to undefined]
**thumbnail_url** | **string** | *Optional*. Url of the thumbnail for the result | [optional] [default to undefined]
**thumbnail_width** | **number** | *Optional*. Thumbnail width | [optional] [default to undefined]
**thumbnail_height** | **number** | *Optional*. Thumbnail height | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultVenue } from 'tele_rest';

const instance: InlineQueryResultVenue = {
    type,
    id,
    latitude,
    longitude,
    title,
    address,
    foursquare_id,
    foursquare_type,
    google_place_id,
    google_place_type,
    reply_markup,
    input_message_content,
    thumbnail_url,
    thumbnail_width,
    thumbnail_height,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
