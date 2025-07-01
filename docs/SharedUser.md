# SharedUser

This object contains information about a user that was shared with the bot using a [KeyboardButtonRequestUsers](https://core.telegram.org/bots/api/#keyboardbuttonrequestusers) button.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **number** | Identifier of the shared user. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so 64-bit integers or double-precision float types are safe for storing these identifiers. The bot may not have access to the user and could be unable to use this identifier, unless the user is already known to the bot by some other means. | [default to undefined]
**first_name** | **string** | *Optional*. First name of the user, if the name was requested by the bot | [optional] [default to undefined]
**last_name** | **string** | *Optional*. Last name of the user, if the name was requested by the bot | [optional] [default to undefined]
**username** | **string** | *Optional*. Username of the user, if the username was requested by the bot | [optional] [default to undefined]
**photo** | [**Array&lt;PhotoSize&gt;**](PhotoSize.md) | *Optional*. Available sizes of the chat photo, if the photo was requested by the bot | [optional] [default to undefined]

## Example

```typescript
import { SharedUser } from 'tele_rest';

const instance: SharedUser = {
    user_id,
    first_name,
    last_name,
    username,
    photo,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
