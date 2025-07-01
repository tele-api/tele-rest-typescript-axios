# ChatMemberOwner

Represents a [chat member](https://core.telegram.org/bots/api/#chatmember) that owns the chat and has all administrator privileges.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **string** | The member\&#39;s status in the chat, always “creator” | [default to 'creator']
**user** | [**User**](User.md) |  | [default to undefined]
**is_anonymous** | **boolean** | *True*, if the user\&#39;s presence in the chat is hidden | [default to undefined]
**custom_title** | **string** | *Optional*. Custom title for this user | [optional] [default to undefined]

## Example

```typescript
import { ChatMemberOwner } from 'tele_rest';

const instance: ChatMemberOwner = {
    status,
    user,
    is_anonymous,
    custom_title,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
