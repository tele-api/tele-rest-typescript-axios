# BanChatMemberPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**BanChatMemberPostRequestChatId**](BanChatMemberPostRequestChatId.md) |  | [default to undefined]
**user_id** | **number** | Unique identifier of the target user | [default to undefined]
**until_date** | **number** | Date when the user will be unbanned; Unix time. If user is banned for more than 366 days or less than 30 seconds from the current time they are considered to be banned forever. Applied for supergroups and channels only. | [optional] [default to undefined]
**revoke_messages** | **boolean** | Pass *True* to delete all messages from the chat for the user that is being removed. If *False*, the user will be able to see messages in the group that were sent before the user was removed. Always *True* for supergroups and channels. | [optional] [default to undefined]

## Example

```typescript
import { BanChatMemberPostRequest } from 'tele_rest';

const instance: BanChatMemberPostRequest = {
    chat_id,
    user_id,
    until_date,
    revoke_messages,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
