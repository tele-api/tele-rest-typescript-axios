# LocationAddress

Describes the physical address of a location.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**country_code** | **string** | The two-letter ISO 3166-1 alpha-2 country code of the country where the location is located | [default to undefined]
**state** | **string** | *Optional*. State of the location | [optional] [default to undefined]
**city** | **string** | *Optional*. City of the location | [optional] [default to undefined]
**street** | **string** | *Optional*. Street address of the location | [optional] [default to undefined]

## Example

```typescript
import { LocationAddress } from 'tele_rest';

const instance: LocationAddress = {
    country_code,
    state,
    city,
    street,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
