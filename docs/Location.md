# Location

This object represents a point on the map.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**latitude** | **number** | Latitude as defined by the sender | [default to undefined]
**longitude** | **number** | Longitude as defined by the sender | [default to undefined]
**horizontal_accuracy** | **number** | *Optional*. The radius of uncertainty for the location, measured in meters; 0-1500 | [optional] [default to undefined]
**live_period** | **number** | *Optional*. Time relative to the message sending date, during which the location can be updated; in seconds. For active live locations only. | [optional] [default to undefined]
**heading** | **number** | *Optional*. The direction in which user is moving, in degrees; 1-360. For active live locations only. | [optional] [default to undefined]
**proximity_alert_radius** | **number** | *Optional*. The maximum distance for proximity alerts about approaching another chat member, in meters. For sent live locations only. | [optional] [default to undefined]

## Example

```typescript
import { Location } from 'tele_rest';

const instance: Location = {
    latitude,
    longitude,
    horizontal_accuracy,
    live_period,
    heading,
    proximity_alert_radius,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
