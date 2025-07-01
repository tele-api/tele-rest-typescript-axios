# ChatMemberLeft

Represents a [chat member](https://core.telegram.org/bots/api/#chatmember) that isn\'t currently a member of the chat, but may join it themselves.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **string** | The member\&#39;s status in the chat, always “left” | [default to 'left']
**user** | [**User**](User.md) |  | [default to undefined]

## Example

```typescript
import { ChatMemberLeft } from 'tele_rest';

const instance: ChatMemberLeft = {
    status,
    user,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
