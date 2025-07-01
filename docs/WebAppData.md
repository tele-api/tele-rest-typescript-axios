# WebAppData

Describes data sent from a [Web App](https://core.telegram.org/bots/webapps) to the bot.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | **string** | The data. Be aware that a bad client can send arbitrary data in this field. | [default to undefined]
**button_text** | **string** | Text of the *web\\_app* keyboard button from which the Web App was opened. Be aware that a bad client can send arbitrary data in this field. | [default to undefined]

## Example

```typescript
import { WebAppData } from 'tele_rest';

const instance: WebAppData = {
    data,
    button_text,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
