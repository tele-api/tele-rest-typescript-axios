# MessageOriginUser

The message was originally sent by a known user.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the message origin, always “user” | [default to 'user']
**date** | **number** | Date the message was sent originally in Unix time | [default to undefined]
**sender_user** | [**User**](User.md) |  | [default to undefined]

## Example

```typescript
import { MessageOriginUser } from 'tele_rest';

const instance: MessageOriginUser = {
    type,
    date,
    sender_user,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
