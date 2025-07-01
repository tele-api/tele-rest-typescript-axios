# UsersShared

This object contains information about the users whose identifiers were shared with the bot using a [KeyboardButtonRequestUsers](https://core.telegram.org/bots/api/#keyboardbuttonrequestusers) button.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **number** | Identifier of the request | [default to undefined]
**users** | [**Array&lt;SharedUser&gt;**](SharedUser.md) | Information about users shared with the bot. | [default to undefined]

## Example

```typescript
import { UsersShared } from 'tele_rest';

const instance: UsersShared = {
    request_id,
    users,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
