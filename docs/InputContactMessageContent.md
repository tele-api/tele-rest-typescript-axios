# InputContactMessageContent

Represents the [content](https://core.telegram.org/bots/api/#inputmessagecontent) of a contact message to be sent as the result of an inline query.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**phone_number** | **string** | Contact\&#39;s phone number | [default to undefined]
**first_name** | **string** | Contact\&#39;s first name | [default to undefined]
**last_name** | **string** | *Optional*. Contact\&#39;s last name | [optional] [default to undefined]
**vcard** | **string** | *Optional*. Additional data about the contact in the form of a [vCard](https://en.wikipedia.org/wiki/VCard), 0-2048 bytes | [optional] [default to undefined]

## Example

```typescript
import { InputContactMessageContent } from 'tele_rest';

const instance: InputContactMessageContent = {
    phone_number,
    first_name,
    last_name,
    vcard,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
