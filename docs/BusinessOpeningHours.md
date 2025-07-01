# BusinessOpeningHours

Describes the opening hours of a business.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**time_zone_name** | **string** | Unique name of the time zone for which the opening hours are defined | [default to undefined]
**opening_hours** | [**Array&lt;BusinessOpeningHoursInterval&gt;**](BusinessOpeningHoursInterval.md) | List of time intervals describing business opening hours | [default to undefined]

## Example

```typescript
import { BusinessOpeningHours } from 'tele_rest';

const instance: BusinessOpeningHours = {
    time_zone_name,
    opening_hours,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
