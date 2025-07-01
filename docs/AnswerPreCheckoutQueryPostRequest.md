# AnswerPreCheckoutQueryPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pre_checkout_query_id** | **string** | Unique identifier for the query to be answered | [default to undefined]
**ok** | **boolean** | Specify *True* if everything is alright (goods are available, etc.) and the bot is ready to proceed with the order. Use *False* if there are any problems. | [default to undefined]
**error_message** | **string** | Required if *ok* is *False*. Error message in human readable form that explains the reason for failure to proceed with the checkout (e.g. \&quot;Sorry, somebody just bought the last of our amazing black T-shirts while you were busy filling out your payment details. Please choose a different color or garment!\&quot;). Telegram will display this message to the user. | [optional] [default to undefined]

## Example

```typescript
import { AnswerPreCheckoutQueryPostRequest } from 'tele_rest';

const instance: AnswerPreCheckoutQueryPostRequest = {
    pre_checkout_query_id,
    ok,
    error_message,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
