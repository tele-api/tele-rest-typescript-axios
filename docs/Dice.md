# Dice

This object represents an animated emoji that displays a random value.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**emoji** | **string** | Emoji on which the dice throw animation is based | [default to undefined]
**value** | **number** | Value of the dice, 1-6 for “🎲”, “🎯” and “🎳” base emoji, 1-5 for “🏀” and “⚽” base emoji, 1-64 for “🎰” base emoji | [default to undefined]

## Example

```typescript
import { Dice } from 'tele_rest';

const instance: Dice = {
    emoji,
    value,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
