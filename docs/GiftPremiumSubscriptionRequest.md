# GiftPremiumSubscriptionRequest

Request parameters for giftPremiumSubscription

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **number** | Unique identifier of the target user who will receive a Telegram Premium subscription | [default to undefined]
**month_count** | **number** | Number of months the Telegram Premium subscription will be active for the user; must be one of 3, 6, or 12 | [default to undefined]
**star_count** | **number** | Number of Telegram Stars to pay for the Telegram Premium subscription; must be 1000 for 3 months, 1500 for 6 months, and 2500 for 12 months | [default to undefined]
**text** | **string** | Text that will be shown along with the service message about the subscription; 0-128 characters | [optional] [default to undefined]
**text_parse_mode** | **string** | Mode for parsing entities in the text. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. Entities other than “bold”, “italic”, “underline”, “strikethrough”, “spoiler”, and “custom\\_emoji” are ignored. | [optional] [default to undefined]
**text_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | A JSON-serialized list of special entities that appear in the gift text. It can be specified instead of *text\\_parse\\_mode*. Entities other than “bold”, “italic”, “underline”, “strikethrough”, “spoiler”, and “custom\\_emoji” are ignored. | [optional] [default to undefined]

## Example

```typescript
import { GiftPremiumSubscriptionRequest } from 'tele_rest';

const instance: GiftPremiumSubscriptionRequest = {
    user_id,
    month_count,
    star_count,
    text,
    text_parse_mode,
    text_entities,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
