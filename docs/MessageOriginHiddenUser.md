# MessageOriginHiddenUser

The message was originally sent by an unknown user.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the message origin, always “hidden\\_user” | [default to 'hidden_user']
**date** | **number** | Date the message was sent originally in Unix time | [default to undefined]
**sender_user_name** | **string** | Name of the user that sent the message originally | [default to undefined]

## Example

```typescript
import { MessageOriginHiddenUser } from 'tele_rest';

const instance: MessageOriginHiddenUser = {
    type,
    date,
    sender_user_name,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
