# PassportElementError

This object represents an error in the Telegram Passport element which was submitted that should be resolved by the user. It should be one of:  * [PassportElementErrorDataField](https://core.telegram.org/bots/api/#passportelementerrordatafield) * [PassportElementErrorFrontSide](https://core.telegram.org/bots/api/#passportelementerrorfrontside) * [PassportElementErrorReverseSide](https://core.telegram.org/bots/api/#passportelementerrorreverseside) * [PassportElementErrorSelfie](https://core.telegram.org/bots/api/#passportelementerrorselfie) * [PassportElementErrorFile](https://core.telegram.org/bots/api/#passportelementerrorfile) * [PassportElementErrorFiles](https://core.telegram.org/bots/api/#passportelementerrorfiles) * [PassportElementErrorTranslationFile](https://core.telegram.org/bots/api/#passportelementerrortranslationfile) * [PassportElementErrorTranslationFiles](https://core.telegram.org/bots/api/#passportelementerrortranslationfiles) * [PassportElementErrorUnspecified](https://core.telegram.org/bots/api/#passportelementerrorunspecified)

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**source** | **string** | Error source, must be *unspecified* | [default to 'unspecified']
**type** | **string** | Type of element of the user\&#39;s Telegram Passport which has the issue | [default to undefined]
**field_name** | **string** | Name of the data field which has the error | [default to undefined]
**data_hash** | **string** | Base64-encoded data hash | [default to undefined]
**message** | **string** | Error message | [default to undefined]
**file_hash** | **string** | Base64-encoded file hash | [default to undefined]
**file_hashes** | **Array&lt;string&gt;** | List of base64-encoded file hashes | [default to undefined]
**element_hash** | **string** | Base64-encoded element hash | [default to undefined]

## Example

```typescript
import { PassportElementError } from 'tele_rest';

const instance: PassportElementError = {
    source,
    type,
    field_name,
    data_hash,
    message,
    file_hash,
    file_hashes,
    element_hash,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
