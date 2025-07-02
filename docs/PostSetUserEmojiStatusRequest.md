# PostSetUserEmojiStatusRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_id** | **number** | Unique identifier of the target user | [default to undefined]
**emoji_status_custom_emoji_id** | **string** | Custom emoji identifier of the emoji status to set. Pass an empty string to remove the status. | [optional] [default to undefined]
**emoji_status_expiration_date** | **number** | Expiration date of the emoji status, if any | [optional] [default to undefined]

## Example

```typescript
import { PostSetUserEmojiStatusRequest } from 'tele_rest';

const instance: PostSetUserEmojiStatusRequest = {
    user_id,
    emoji_status_custom_emoji_id,
    emoji_status_expiration_date,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
