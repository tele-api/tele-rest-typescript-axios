# KeyboardButtonRequestUsers

This object defines the criteria used to request suitable users. Information about the selected users will be shared with the bot when the corresponding button is pressed. [More about requesting users »](https://core.telegram.org/bots/features#chat-and-user-selection)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **number** | Signed 32-bit identifier of the request that will be received back in the [UsersShared](https://core.telegram.org/bots/api/#usersshared) object. Must be unique within the message | [default to undefined]
**user_is_bot** | **boolean** | *Optional*. Pass *True* to request bots, pass *False* to request regular users. If not specified, no additional restrictions are applied. | [optional] [default to undefined]
**user_is_premium** | **boolean** | *Optional*. Pass *True* to request premium users, pass *False* to request non-premium users. If not specified, no additional restrictions are applied. | [optional] [default to undefined]
**max_quantity** | **number** | *Optional*. The maximum number of users to be selected; 1-10. Defaults to 1. | [optional] [default to 1]
**request_name** | **boolean** | *Optional*. Pass *True* to request the users\&#39; first and last names | [optional] [default to undefined]
**request_username** | **boolean** | *Optional*. Pass *True* to request the users\&#39; usernames | [optional] [default to undefined]
**request_photo** | **boolean** | *Optional*. Pass *True* to request the users\&#39; photos | [optional] [default to undefined]

## Example

```typescript
import { KeyboardButtonRequestUsers } from 'tele_rest';

const instance: KeyboardButtonRequestUsers = {
    request_id,
    user_is_bot,
    user_is_premium,
    max_quantity,
    request_name,
    request_username,
    request_photo,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
