# ChatMemberBanned

Represents a [chat member](https://core.telegram.org/bots/api/#chatmember) that was banned in the chat and can\'t return to the chat or view chat messages.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **string** | The member\&#39;s status in the chat, always “kicked” | [default to 'kicked']
**user** | [**User**](User.md) |  | [default to undefined]
**until_date** | **number** | Date when restrictions will be lifted for this user; Unix time. If 0, then the user is banned forever | [default to undefined]

## Example

```typescript
import { ChatMemberBanned } from 'tele_rest';

const instance: ChatMemberBanned = {
    status,
    user,
    until_date,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
