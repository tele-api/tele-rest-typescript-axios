# InputLocationMessageContent

Represents the [content](https://core.telegram.org/bots/api/#inputmessagecontent) of a location message to be sent as the result of an inline query.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**latitude** | **number** | Latitude of the location in degrees | [default to undefined]
**longitude** | **number** | Longitude of the location in degrees | [default to undefined]
**horizontal_accuracy** | **number** | *Optional*. The radius of uncertainty for the location, measured in meters; 0-1500 | [optional] [default to undefined]
**live_period** | **number** | *Optional*. Period in seconds during which the location can be updated, should be between 60 and 86400, or 0x7FFFFFFF for live locations that can be edited indefinitely. | [optional] [default to undefined]
**heading** | **number** | *Optional*. For live locations, a direction in which the user is moving, in degrees. Must be between 1 and 360 if specified. | [optional] [default to undefined]
**proximity_alert_radius** | **number** | *Optional*. For live locations, a maximum distance for proximity alerts about approaching another chat member, in meters. Must be between 1 and 100000 if specified. | [optional] [default to undefined]

## Example

```typescript
import { InputLocationMessageContent } from 'tele_rest';

const instance: InputLocationMessageContent = {
    latitude,
    longitude,
    horizontal_accuracy,
    live_period,
    heading,
    proximity_alert_radius,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
