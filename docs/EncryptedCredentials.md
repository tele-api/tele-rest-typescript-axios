# EncryptedCredentials

Describes data required for decrypting and authenticating [EncryptedPassportElement](https://core.telegram.org/bots/api/#encryptedpassportelement). See the [Telegram Passport Documentation](https://core.telegram.org/passport#receiving-information) for a complete description of the data decryption and authentication processes.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | **string** | Base64-encoded encrypted JSON-serialized data with unique user\&#39;s payload, data hashes and secrets required for [EncryptedPassportElement](https://core.telegram.org/bots/api/#encryptedpassportelement) decryption and authentication | [default to undefined]
**hash** | **string** | Base64-encoded data hash for data authentication | [default to undefined]
**secret** | **string** | Base64-encoded secret, encrypted with the bot\&#39;s public RSA key, required for data decryption | [default to undefined]

## Example

```typescript
import { EncryptedCredentials } from 'tele_rest';

const instance: EncryptedCredentials = {
    data,
    hash,
    secret,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
