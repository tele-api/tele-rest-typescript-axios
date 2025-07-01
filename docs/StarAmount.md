# StarAmount

Describes an amount of Telegram Stars.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**amount** | **number** | Integer amount of Telegram Stars, rounded to 0; can be negative | [default to undefined]
**nanostar_amount** | **number** | *Optional*. The number of 1/1000000000 shares of Telegram Stars; from -999999999 to 999999999; can be negative if and only if *amount* is non-positive | [optional] [default to undefined]

## Example

```typescript
import { StarAmount } from 'tele_rest';

const instance: StarAmount = {
    amount,
    nanostar_amount,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
