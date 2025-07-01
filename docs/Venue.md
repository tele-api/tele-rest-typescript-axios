# Venue

This object represents a venue.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**location** | [**Location**](Location.md) |  | [default to undefined]
**title** | **string** | Name of the venue | [default to undefined]
**address** | **string** | Address of the venue | [default to undefined]
**foursquare_id** | **string** | *Optional*. Foursquare identifier of the venue | [optional] [default to undefined]
**foursquare_type** | **string** | *Optional*. Foursquare type of the venue. (For example, “arts\\_entertainment/default”, “arts\\_entertainment/aquarium” or “food/icecream”.) | [optional] [default to undefined]
**google_place_id** | **string** | *Optional*. Google Places identifier of the venue | [optional] [default to undefined]
**google_place_type** | **string** | *Optional*. Google Places type of the venue. (See [supported types](https://developers.google.com/places/web-service/supported_types).) | [optional] [default to undefined]

## Example

```typescript
import { Venue } from 'tele_rest';

const instance: Venue = {
    location,
    title,
    address,
    foursquare_id,
    foursquare_type,
    google_place_id,
    google_place_type,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
