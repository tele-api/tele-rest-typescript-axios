# ShippingAddress

This object represents a shipping address.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**country_code** | **string** | Two-letter [ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) country code | [default to undefined]
**state** | **string** | State, if applicable | [default to undefined]
**city** | **string** | City | [default to undefined]
**street_line1** | **string** | First line for the address | [default to undefined]
**street_line2** | **string** | Second line for the address | [default to undefined]
**post_code** | **string** | Address post code | [default to undefined]

## Example

```typescript
import { ShippingAddress } from 'tele_rest';

const instance: ShippingAddress = {
    country_code,
    state,
    city,
    street_line1,
    street_line2,
    post_code,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
