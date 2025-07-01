# ChatInviteLink

Represents an invite link for a chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invite_link** | **string** | The invite link. If the link was created by another chat administrator, then the second part of the link will be replaced with “…”. | [default to undefined]
**creator** | [**User**](User.md) |  | [default to undefined]
**creates_join_request** | **boolean** | *True*, if users joining the chat via the link need to be approved by chat administrators | [default to undefined]
**is_primary** | **boolean** | *True*, if the link is primary | [default to undefined]
**is_revoked** | **boolean** | *True*, if the link is revoked | [default to undefined]
**name** | **string** | *Optional*. Invite link name | [optional] [default to undefined]
**expire_date** | **number** | *Optional*. Point in time (Unix timestamp) when the link will expire or has been expired | [optional] [default to undefined]
**member_limit** | **number** | *Optional*. The maximum number of users that can be members of the chat simultaneously after joining the chat via this invite link; 1-99999 | [optional] [default to undefined]
**pending_join_request_count** | **number** | *Optional*. Number of pending join requests created using this link | [optional] [default to undefined]
**subscription_period** | **number** | *Optional*. The number of seconds the subscription will be active for before the next payment | [optional] [default to undefined]
**subscription_price** | **number** | *Optional*. The amount of Telegram Stars a user must pay initially and after each subsequent subscription period to be a member of the chat using the link | [optional] [default to undefined]

## Example

```typescript
import { ChatInviteLink } from 'tele_rest';

const instance: ChatInviteLink = {
    invite_link,
    creator,
    creates_join_request,
    is_primary,
    is_revoked,
    name,
    expire_date,
    member_limit,
    pending_join_request_count,
    subscription_period,
    subscription_price,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
