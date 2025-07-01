# OwnedGifts

Contains the list of gifts received and owned by a user or a chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**total_count** | **number** | The total number of gifts owned by the user or the chat | [default to undefined]
**gifts** | [**Array&lt;OwnedGift&gt;**](OwnedGift.md) | The list of gifts | [default to undefined]
**next_offset** | **string** | *Optional*. Offset for the next request. If empty, then there are no more results | [optional] [default to undefined]

## Example

```typescript
import { OwnedGifts } from 'tele_rest';

const instance: OwnedGifts = {
    total_count,
    gifts,
    next_offset,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
