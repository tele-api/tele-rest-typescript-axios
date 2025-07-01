# UpgradeGiftPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection | [default to undefined]
**owned_gift_id** | **string** | Unique identifier of the regular gift that should be upgraded to a unique one | [default to undefined]
**keep_original_details** | **boolean** | Pass True to keep the original gift text, sender and receiver in the upgraded gift | [optional] [default to undefined]
**star_count** | **number** | The amount of Telegram Stars that will be paid for the upgrade from the business account balance. If &#x60;gift.prepaid_upgrade_star_count &gt; 0&#x60;, then pass 0, otherwise, the *can\\_transfer\\_stars* business bot right is required and &#x60;gift.upgrade_star_count&#x60; must be passed. | [optional] [default to undefined]

## Example

```typescript
import { UpgradeGiftPostRequest } from 'tele_rest';

const instance: UpgradeGiftPostRequest = {
    business_connection_id,
    owned_gift_id,
    keep_original_details,
    star_count,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
