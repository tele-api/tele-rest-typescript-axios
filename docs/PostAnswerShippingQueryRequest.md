# PostAnswerShippingQueryRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**shipping_query_id** | **string** | Unique identifier for the query to be answered | [default to undefined]
**ok** | **boolean** | Pass *True* if delivery to the specified address is possible and *False* if there are any problems (for example, if delivery to the specified address is not possible) | [default to undefined]
**shipping_options** | [**Array&lt;ShippingOption&gt;**](ShippingOption.md) | Required if *ok* is *True*. A JSON-serialized array of available shipping options. | [optional] [default to undefined]
**error_message** | **string** | Required if *ok* is *False*. Error message in human readable form that explains why it is impossible to complete the order (e.g. “Sorry, delivery to your desired address is unavailable”). Telegram will display this message to the user. | [optional] [default to undefined]

## Example

```typescript
import { PostAnswerShippingQueryRequest } from 'tele_rest';

const instance: PostAnswerShippingQueryRequest = {
    shipping_query_id,
    ok,
    shipping_options,
    error_message,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
