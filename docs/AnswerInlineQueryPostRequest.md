# AnswerInlineQueryPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inline_query_id** | **string** | Unique identifier for the answered query | [default to undefined]
**results** | [**Array&lt;InlineQueryResult&gt;**](InlineQueryResult.md) | A JSON-serialized array of results for the inline query | [default to undefined]
**cache_time** | **number** | The maximum amount of time in seconds that the result of the inline query may be cached on the server. Defaults to 300. | [optional] [default to 300]
**is_personal** | **boolean** | Pass *True* if results may be cached on the server side only for the user that sent the query. By default, results may be returned to any user who sends the same query. | [optional] [default to undefined]
**next_offset** | **string** | Pass the offset that a client should send in the next query with the same text to receive more results. Pass an empty string if there are no more results or if you don\&#39;t support pagination. Offset length can\&#39;t exceed 64 bytes. | [optional] [default to undefined]
**button** | [**InlineQueryResultsButton**](InlineQueryResultsButton.md) |  | [optional] [default to undefined]

## Example

```typescript
import { AnswerInlineQueryPostRequest } from 'tele_rest';

const instance: AnswerInlineQueryPostRequest = {
    inline_query_id,
    results,
    cache_time,
    is_personal,
    next_offset,
    button,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
