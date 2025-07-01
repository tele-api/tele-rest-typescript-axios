# ProximityAlertTriggered

This object represents the content of a service message, sent whenever a user in the chat triggers a proximity alert set by another user.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**traveler** | [**User**](User.md) |  | [default to undefined]
**watcher** | [**User**](User.md) |  | [default to undefined]
**distance** | **number** | The distance between the users | [default to undefined]

## Example

```typescript
import { ProximityAlertTriggered } from 'tele_rest';

const instance: ProximityAlertTriggered = {
    traveler,
    watcher,
    distance,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
