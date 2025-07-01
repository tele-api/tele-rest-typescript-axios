# PreparedInlineMessage

Describes an inline message to be sent by a user of a Mini App.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier of the prepared message | [default to undefined]
**expiration_date** | **number** | Expiration date of the prepared message, in Unix time. Expired prepared messages can no longer be used | [default to undefined]

## Example

```typescript
import { PreparedInlineMessage } from 'tele_rest';

const instance: PreparedInlineMessage = {
    id,
    expiration_date,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
