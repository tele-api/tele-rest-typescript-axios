# KeyboardButton

This object represents one button of the reply keyboard. At most one of the optional fields must be used to specify type of the button. For simple text buttons, *String* can be used instead of this object to specify the button text.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **string** | Text of the button. If none of the optional fields are used, it will be sent as a message when the button is pressed | [default to undefined]
**request_users** | [**KeyboardButtonRequestUsers**](KeyboardButtonRequestUsers.md) |  | [optional] [default to undefined]
**request_chat** | [**KeyboardButtonRequestChat**](KeyboardButtonRequestChat.md) |  | [optional] [default to undefined]
**request_contact** | **boolean** | *Optional*. If *True*, the user\&#39;s phone number will be sent as a contact when the button is pressed. Available in private chats only. | [optional] [default to undefined]
**request_location** | **boolean** | *Optional*. If *True*, the user\&#39;s current location will be sent when the button is pressed. Available in private chats only. | [optional] [default to undefined]
**request_poll** | [**KeyboardButtonPollType**](KeyboardButtonPollType.md) |  | [optional] [default to undefined]
**web_app** | [**WebAppInfo**](WebAppInfo.md) |  | [optional] [default to undefined]

## Example

```typescript
import { KeyboardButton } from 'tele_rest';

const instance: KeyboardButton = {
    text,
    request_users,
    request_chat,
    request_contact,
    request_location,
    request_poll,
    web_app,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
