# ReactionTypeCustomEmoji

The reaction is based on a custom emoji.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the reaction, always “custom\\_emoji” | [default to 'custom_emoji']
**custom_emoji_id** | **string** | Custom emoji identifier | [default to undefined]

## Example

```typescript
import { ReactionTypeCustomEmoji } from 'tele_rest';

const instance: ReactionTypeCustomEmoji = {
    type,
    custom_emoji_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
