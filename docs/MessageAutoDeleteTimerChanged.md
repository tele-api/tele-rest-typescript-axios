# MessageAutoDeleteTimerChanged

This object represents a service message about a change in auto-delete timer settings.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message_auto_delete_time** | **number** | New auto-delete time for messages in the chat; in seconds | [default to undefined]

## Example

```typescript
import { MessageAutoDeleteTimerChanged } from 'tele_rest';

const instance: MessageAutoDeleteTimerChanged = {
    message_auto_delete_time,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
