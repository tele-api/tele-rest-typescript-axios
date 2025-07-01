# MenuButton

This object describes the bot\'s menu button in a private chat. It should be one of  * [MenuButtonCommands](https://core.telegram.org/bots/api/#menubuttoncommands) * [MenuButtonWebApp](https://core.telegram.org/bots/api/#menubuttonwebapp) * [MenuButtonDefault](https://core.telegram.org/bots/api/#menubuttondefault)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the button, must be *default* | [default to 'default']
**text** | **string** | Text on the button | [default to undefined]
**web_app** | [**WebAppInfo**](WebAppInfo.md) |  | [default to undefined]

## Example

```typescript
import { MenuButton } from 'tele_rest';

const instance: MenuButton = {
    type,
    text,
    web_app,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
