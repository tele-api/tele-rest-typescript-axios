# PassportData

Describes Telegram Passport data shared with the bot by the user.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**Array&lt;EncryptedPassportElement&gt;**](EncryptedPassportElement.md) | Array with information about documents and other Telegram Passport elements that was shared with the bot | [default to undefined]
**credentials** | [**EncryptedCredentials**](EncryptedCredentials.md) |  | [default to undefined]

## Example

```typescript
import { PassportData } from 'tele_rest';

const instance: PassportData = {
    data,
    credentials,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
