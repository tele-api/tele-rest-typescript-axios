# PaidMediaInfo

Describes the paid media added to a message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**star_count** | **number** | The number of Telegram Stars that must be paid to buy access to the media | [default to undefined]
**paid_media** | [**Array&lt;PaidMedia&gt;**](PaidMedia.md) | Information about the paid media | [default to undefined]

## Example

```typescript
import { PaidMediaInfo } from 'tele_rest';

const instance: PaidMediaInfo = {
    star_count,
    paid_media,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
