# GetStarTransactionsRequest

Request parameters for getStarTransactions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**offset** | **number** | Number of transactions to skip in the response | [optional] [default to undefined]
**limit** | **number** | The maximum number of transactions to be retrieved. Values between 1-100 are accepted. Defaults to 100. | [optional] [default to 100]

## Example

```typescript
import { GetStarTransactionsRequest } from 'tele_rest';

const instance: GetStarTransactionsRequest = {
    offset,
    limit,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
