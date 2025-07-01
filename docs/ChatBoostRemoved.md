# ChatBoostRemoved

This object represents a boost removed from a chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat** | [**Chat**](Chat.md) |  | [default to undefined]
**boost_id** | **string** | Unique identifier of the boost | [default to undefined]
**remove_date** | **number** | Point in time (Unix timestamp) when the boost was removed | [default to undefined]
**source** | [**ChatBoostSource**](ChatBoostSource.md) |  | [default to undefined]

## Example

```typescript
import { ChatBoostRemoved } from 'tele_rest';

const instance: ChatBoostRemoved = {
    chat,
    boost_id,
    remove_date,
    source,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
