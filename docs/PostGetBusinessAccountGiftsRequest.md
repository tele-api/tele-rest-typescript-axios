# PostGetBusinessAccountGiftsRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection | [default to undefined]
**exclude_unsaved** | **boolean** | Pass True to exclude gifts that aren\&#39;t saved to the account\&#39;s profile page | [optional] [default to undefined]
**exclude_saved** | **boolean** | Pass True to exclude gifts that are saved to the account\&#39;s profile page | [optional] [default to undefined]
**exclude_unlimited** | **boolean** | Pass True to exclude gifts that can be purchased an unlimited number of times | [optional] [default to undefined]
**exclude_limited** | **boolean** | Pass True to exclude gifts that can be purchased a limited number of times | [optional] [default to undefined]
**exclude_unique** | **boolean** | Pass True to exclude unique gifts | [optional] [default to undefined]
**sort_by_price** | **boolean** | Pass True to sort results by gift price instead of send date. Sorting is applied before pagination. | [optional] [default to undefined]
**offset** | **string** | Offset of the first entry to return as received from the previous request; use empty string to get the first chunk of results | [optional] [default to undefined]
**limit** | **number** | The maximum number of gifts to be returned; 1-100. Defaults to 100 | [optional] [default to 100]

## Example

```typescript
import { PostGetBusinessAccountGiftsRequest } from 'tele_rest';

const instance: PostGetBusinessAccountGiftsRequest = {
    business_connection_id,
    exclude_unsaved,
    exclude_saved,
    exclude_unlimited,
    exclude_limited,
    exclude_unique,
    sort_by_price,
    offset,
    limit,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
