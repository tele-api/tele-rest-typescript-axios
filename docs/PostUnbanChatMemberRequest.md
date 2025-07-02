# PostUnbanChatMemberRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**PostBanChatMemberRequestChatId**](PostBanChatMemberRequestChatId.md) |  | [default to undefined]
**user_id** | **number** | Unique identifier of the target user | [default to undefined]
**only_if_banned** | **boolean** | Do nothing if the user is not banned | [optional] [default to undefined]

## Example

```typescript
import { PostUnbanChatMemberRequest } from 'tele_rest';

const instance: PostUnbanChatMemberRequest = {
    chat_id,
    user_id,
    only_if_banned,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
