# AnswerWebAppQueryRequest

Request parameters for answerWebAppQuery

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**web_app_query_id** | **string** | Unique identifier for the query to be answered | [default to undefined]
**result** | [**InlineQueryResult**](InlineQueryResult.md) |  | [default to undefined]

## Example

```typescript
import { AnswerWebAppQueryRequest } from 'tele_rest';

const instance: AnswerWebAppQueryRequest = {
    web_app_query_id,
    result,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
