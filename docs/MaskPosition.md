# MaskPosition

This object describes the position on faces where a mask should be placed by default.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**point** | **string** | The part of the face relative to which the mask should be placed. One of “forehead”, “eyes”, “mouth”, or “chin”. | [default to undefined]
**x_shift** | **number** | Shift by X-axis measured in widths of the mask scaled to the face size, from left to right. For example, choosing -1.0 will place mask just to the left of the default mask position. | [default to undefined]
**y_shift** | **number** | Shift by Y-axis measured in heights of the mask scaled to the face size, from top to bottom. For example, 1.0 will place the mask just below the default mask position. | [default to undefined]
**scale** | **number** | Mask scaling coefficient. For example, 2.0 means double size. | [default to undefined]

## Example

```typescript
import { MaskPosition } from 'tele_rest';

const instance: MaskPosition = {
    point,
    x_shift,
    y_shift,
    scale,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
