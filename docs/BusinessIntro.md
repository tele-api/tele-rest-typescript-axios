# BusinessIntro

Contains information about the start page settings of a Telegram Business account.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **string** | *Optional*. Title text of the business intro | [optional] [default to undefined]
**message** | **string** | *Optional*. Message text of the business intro | [optional] [default to undefined]
**sticker** | [**Sticker**](Sticker.md) |  | [optional] [default to undefined]

## Example

```typescript
import { BusinessIntro } from 'tele_rest';

const instance: BusinessIntro = {
    title,
    message,
    sticker,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
