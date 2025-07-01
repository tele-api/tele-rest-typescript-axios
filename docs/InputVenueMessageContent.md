# InputVenueMessageContent

Represents the [content](https://core.telegram.org/bots/api/#inputmessagecontent) of a venue message to be sent as the result of an inline query.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**latitude** | **number** | Latitude of the venue in degrees | [default to undefined]
**longitude** | **number** | Longitude of the venue in degrees | [default to undefined]
**title** | **string** | Name of the venue | [default to undefined]
**address** | **string** | Address of the venue | [default to undefined]
**foursquare_id** | **string** | *Optional*. Foursquare identifier of the venue, if known | [optional] [default to undefined]
**foursquare_type** | **string** | *Optional*. Foursquare type of the venue, if known. (For example, “arts\\_entertainment/default”, “arts\\_entertainment/aquarium” or “food/icecream”.) | [optional] [default to undefined]
**google_place_id** | **string** | *Optional*. Google Places identifier of the venue | [optional] [default to undefined]
**google_place_type** | **string** | *Optional*. Google Places type of the venue. (See [supported types](https://developers.google.com/places/web-service/supported_types).) | [optional] [default to undefined]

## Example

```typescript
import { InputVenueMessageContent } from 'tele_rest';

const instance: InputVenueMessageContent = {
    latitude,
    longitude,
    title,
    address,
    foursquare_id,
    foursquare_type,
    google_place_id,
    google_place_type,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
