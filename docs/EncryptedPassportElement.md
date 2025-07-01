# EncryptedPassportElement

Describes documents or other Telegram Passport elements shared with the bot by the user.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Element type. One of “personal\\_details”, “passport”, “driver\\_license”, “identity\\_card”, “internal\\_passport”, “address”, “utility\\_bill”, “bank\\_statement”, “rental\\_agreement”, “passport\\_registration”, “temporary\\_registration”, “phone\\_number”, “email”. | [default to undefined]
**hash** | **string** | Base64-encoded element hash for using in [PassportElementErrorUnspecified](https://core.telegram.org/bots/api/#passportelementerrorunspecified) | [default to undefined]
**data** | **string** | *Optional*. Base64-encoded encrypted Telegram Passport element data provided by the user; available only for “personal\\_details”, “passport”, “driver\\_license”, “identity\\_card”, “internal\\_passport” and “address” types. Can be decrypted and verified using the accompanying [EncryptedCredentials](https://core.telegram.org/bots/api/#encryptedcredentials). | [optional] [default to undefined]
**phone_number** | **string** | *Optional*. User\&#39;s verified phone number; available only for “phone\\_number” type | [optional] [default to undefined]
**email** | **string** | *Optional*. User\&#39;s verified email address; available only for “email” type | [optional] [default to undefined]
**files** | [**Array&lt;PassportFile&gt;**](PassportFile.md) | *Optional*. Array of encrypted files with documents provided by the user; available only for “utility\\_bill”, “bank\\_statement”, “rental\\_agreement”, “passport\\_registration” and “temporary\\_registration” types. Files can be decrypted and verified using the accompanying [EncryptedCredentials](https://core.telegram.org/bots/api/#encryptedcredentials). | [optional] [default to undefined]
**front_side** | [**PassportFile**](PassportFile.md) |  | [optional] [default to undefined]
**reverse_side** | [**PassportFile**](PassportFile.md) |  | [optional] [default to undefined]
**selfie** | [**PassportFile**](PassportFile.md) |  | [optional] [default to undefined]
**translation** | [**Array&lt;PassportFile&gt;**](PassportFile.md) | *Optional*. Array of encrypted files with translated versions of documents provided by the user; available if requested for “passport”, “driver\\_license”, “identity\\_card”, “internal\\_passport”, “utility\\_bill”, “bank\\_statement”, “rental\\_agreement”, “passport\\_registration” and “temporary\\_registration” types. Files can be decrypted and verified using the accompanying [EncryptedCredentials](https://core.telegram.org/bots/api/#encryptedcredentials). | [optional] [default to undefined]

## Example

```typescript
import { EncryptedPassportElement } from 'tele_rest';

const instance: EncryptedPassportElement = {
    type,
    hash,
    data,
    phone_number,
    email,
    files,
    front_side,
    reverse_side,
    selfie,
    translation,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
