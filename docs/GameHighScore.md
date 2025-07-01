# GameHighScore

This object represents one row of the high scores table for a game.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**position** | **number** | Position in high score table for the game | [default to undefined]
**user** | [**User**](User.md) |  | [default to undefined]
**score** | **number** | Score | [default to undefined]

## Example

```typescript
import { GameHighScore } from 'tele_rest';

const instance: GameHighScore = {
    position,
    user,
    score,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
