# ChatBoost

This object contains information about a chat boost.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**boost_id** | **string** | Unique identifier of the boost | [default to undefined]
**add_date** | **number** | Point in time (Unix timestamp) when the chat was boosted | [default to undefined]
**expiration_date** | **number** | Point in time (Unix timestamp) when the boost will automatically expire, unless the booster\&#39;s Telegram Premium subscription is prolonged | [default to undefined]
**source** | [**ChatBoostSource**](ChatBoostSource.md) |  | [default to undefined]

## Example

```typescript
import { ChatBoost } from 'tele_rest';

const instance: ChatBoost = {
    boost_id,
    add_date,
    expiration_date,
    source,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
