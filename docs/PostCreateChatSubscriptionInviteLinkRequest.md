# PostCreateChatSubscriptionInviteLinkRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**PostCreateChatSubscriptionInviteLinkRequestChatId**](PostCreateChatSubscriptionInviteLinkRequestChatId.md) |  | [default to undefined]
**subscription_period** | **number** | The number of seconds the subscription will be active for before the next payment. Currently, it must always be 2592000 (30 days). | [default to undefined]
**subscription_price** | **number** | The amount of Telegram Stars a user must pay initially and after each subsequent subscription period to be a member of the chat; 1-10000 | [default to undefined]
**name** | **string** | Invite link name; 0-32 characters | [optional] [default to undefined]

## Example

```typescript
import { PostCreateChatSubscriptionInviteLinkRequest } from 'tele_rest';

const instance: PostCreateChatSubscriptionInviteLinkRequest = {
    chat_id,
    subscription_period,
    subscription_price,
    name,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
