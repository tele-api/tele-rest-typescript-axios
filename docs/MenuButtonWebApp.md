# MenuButtonWebApp

Represents a menu button, which launches a [Web App](https://core.telegram.org/bots/webapps).

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the button, must be *web\\_app* | [default to 'web_app']
**text** | **string** | Text on the button | [default to undefined]
**web_app** | [**WebAppInfo**](WebAppInfo.md) |  | [default to undefined]

## Example

```typescript
import { MenuButtonWebApp } from 'tele_rest';

const instance: MenuButtonWebApp = {
    type,
    text,
    web_app,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
