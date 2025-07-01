# ResponseParameters

Describes why a request was unsuccessful.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**migrate_to_chat_id** | **number** | *Optional*. The group has been migrated to a supergroup with the specified identifier. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a signed 64-bit integer or double-precision float type are safe for storing this identifier. | [optional] [default to undefined]
**retry_after** | **number** | *Optional*. In case of exceeding flood control, the number of seconds left to wait before the request can be repeated | [optional] [default to undefined]

## Example

```typescript
import { ResponseParameters } from 'tele_rest';

const instance: ResponseParameters = {
    migrate_to_chat_id,
    retry_after,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
