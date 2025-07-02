# PostSetBusinessAccountGiftSettingsRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_connection_id** | **string** | Unique identifier of the business connection | [default to undefined]
**show_gift_button** | **boolean** | Pass True, if a button for sending a gift to the user or by the business account must always be shown in the input field | [default to undefined]
**accepted_gift_types** | [**AcceptedGiftTypes**](AcceptedGiftTypes.md) |  | [default to undefined]

## Example

```typescript
import { PostSetBusinessAccountGiftSettingsRequest } from 'tele_rest';

const instance: PostSetBusinessAccountGiftSettingsRequest = {
    business_connection_id,
    show_gift_button,
    accepted_gift_types,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
