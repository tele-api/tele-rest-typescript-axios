# RestrictChatMemberPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**RestrictChatMemberPostRequestChatId**](RestrictChatMemberPostRequestChatId.md) |  | [default to undefined]
**user_id** | **number** | Unique identifier of the target user | [default to undefined]
**permissions** | [**ChatPermissions**](ChatPermissions.md) |  | [default to undefined]
**use_independent_chat_permissions** | **boolean** | Pass *True* if chat permissions are set independently. Otherwise, the *can\\_send\\_other\\_messages* and *can\\_add\\_web\\_page\\_previews* permissions will imply the *can\\_send\\_messages*, *can\\_send\\_audios*, *can\\_send\\_documents*, *can\\_send\\_photos*, *can\\_send\\_videos*, *can\\_send\\_video\\_notes*, and *can\\_send\\_voice\\_notes* permissions; the *can\\_send\\_polls* permission will imply the *can\\_send\\_messages* permission. | [optional] [default to undefined]
**until_date** | **number** | Date when restrictions will be lifted for the user; Unix time. If user is restricted for more than 366 days or less than 30 seconds from the current time, they are considered to be restricted forever | [optional] [default to undefined]

## Example

```typescript
import { RestrictChatMemberPostRequest } from 'tele_rest';

const instance: RestrictChatMemberPostRequest = {
    chat_id,
    user_id,
    permissions,
    use_independent_chat_permissions,
    until_date,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
