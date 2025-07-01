# BotCommand

This object represents a bot command.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**command** | **string** | Text of the command; 1-32 characters. Can contain only lowercase English letters, digits and underscores. | [default to undefined]
**description** | **string** | Description of the command; 1-256 characters. | [default to undefined]

## Example

```typescript
import { BotCommand } from 'tele_rest';

const instance: BotCommand = {
    command,
    description,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
