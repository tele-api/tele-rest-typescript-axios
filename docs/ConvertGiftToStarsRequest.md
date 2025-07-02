# ConvertGiftToStarsRequest

Request parameters for convertGiftToStars

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection | [default to undefined]
**owned_gift_id** | **string** | Unique identifier of the regular gift that should be converted to Telegram Stars | [default to undefined]

## Example

```typescript
import { ConvertGiftToStarsRequest } from 'tele_rest';

const instance: ConvertGiftToStarsRequest = {
    business_connection_id,
    owned_gift_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
