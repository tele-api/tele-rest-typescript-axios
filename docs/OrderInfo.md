# OrderInfo

This object represents information about an order.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | *Optional*. User name | [optional] [default to undefined]
**phone_number** | **string** | *Optional*. User\&#39;s phone number | [optional] [default to undefined]
**email** | **string** | *Optional*. User email | [optional] [default to undefined]
**shipping_address** | [**ShippingAddress**](ShippingAddress.md) |  | [optional] [default to undefined]

## Example

```typescript
import { OrderInfo } from 'tele_rest';

const instance: OrderInfo = {
    name,
    phone_number,
    email,
    shipping_address,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
