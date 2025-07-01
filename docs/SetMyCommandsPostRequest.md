# SetMyCommandsPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**commands** | [**Array&lt;BotCommand&gt;**](BotCommand.md) | A JSON-serialized list of bot commands to be set as the list of the bot\&#39;s commands. At most 100 commands can be specified. | [default to undefined]
**scope** | [**BotCommandScope**](BotCommandScope.md) |  | [optional] [default to undefined]
**language_code** | **string** | A two-letter ISO 639-1 language code. If empty, commands will be applied to all users from the given scope, for whose language there are no dedicated commands | [optional] [default to undefined]

## Example

```typescript
import { SetMyCommandsPostRequest } from 'tele_rest';

const instance: SetMyCommandsPostRequest = {
    commands,
    scope,
    language_code,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
