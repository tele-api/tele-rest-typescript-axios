# BackgroundFillFreeformGradient

The background is a freeform gradient that rotates after every message in the chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the background fill, always “freeform\\_gradient” | [default to 'freeform_gradient']
**colors** | **Array&lt;number&gt;** | A list of the 3 or 4 base colors that are used to generate the freeform gradient in the RGB24 format | [default to undefined]

## Example

```typescript
import { BackgroundFillFreeformGradient } from 'tele_rest';

const instance: BackgroundFillFreeformGradient = {
    type,
    colors,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
