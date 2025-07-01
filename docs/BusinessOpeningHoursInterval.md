# BusinessOpeningHoursInterval

Describes an interval of time during which a business is open.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**opening_minute** | **number** | The minute\&#39;s sequence number in a week, starting on Monday, marking the start of the time interval during which the business is open; 0 - 7 \\* 24 \\* 60 | [default to undefined]
**closing_minute** | **number** | The minute\&#39;s sequence number in a week, starting on Monday, marking the end of the time interval during which the business is open; 0 - 8 \\* 24 \\* 60 | [default to undefined]

## Example

```typescript
import { BusinessOpeningHoursInterval } from 'tele_rest';

const instance: BusinessOpeningHoursInterval = {
    opening_minute,
    closing_minute,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
