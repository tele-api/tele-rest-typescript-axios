# ShippingQuery

This object contains information about an incoming shipping query.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique query identifier | [default to undefined]
**from** | [**User**](User.md) |  | [default to undefined]
**invoice_payload** | **string** | Bot-specified invoice payload | [default to undefined]
**shipping_address** | [**ShippingAddress**](ShippingAddress.md) |  | [default to undefined]

## Example

```typescript
import { ShippingQuery } from 'tele_rest';

const instance: ShippingQuery = {
    id,
    from,
    invoice_payload,
    shipping_address,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
