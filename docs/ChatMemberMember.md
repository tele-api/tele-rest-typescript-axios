# ChatMemberMember

Represents a [chat member](https://core.telegram.org/bots/api/#chatmember) that has no additional privileges or restrictions.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **string** | The member\&#39;s status in the chat, always “member” | [default to 'member']
**user** | [**User**](User.md) |  | [default to undefined]
**until_date** | **number** | *Optional*. Date when the user\&#39;s subscription will expire; Unix time | [optional] [default to undefined]

## Example

```typescript
import { ChatMemberMember } from 'tele_rest';

const instance: ChatMemberMember = {
    status,
    user,
    until_date,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
