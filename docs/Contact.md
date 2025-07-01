# Contact

This object represents a phone contact.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**phone_number** | **string** | Contact\&#39;s phone number | [default to undefined]
**first_name** | **string** | Contact\&#39;s first name | [default to undefined]
**last_name** | **string** | *Optional*. Contact\&#39;s last name | [optional] [default to undefined]
**user_id** | **number** | *Optional*. Contact\&#39;s user identifier in Telegram. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a 64-bit integer or double-precision float type are safe for storing this identifier. | [optional] [default to undefined]
**vcard** | **string** | *Optional*. Additional data about the contact in the form of a [vCard](https://en.wikipedia.org/wiki/VCard) | [optional] [default to undefined]

## Example

```typescript
import { Contact } from 'tele_rest';

const instance: Contact = {
    phone_number,
    first_name,
    last_name,
    user_id,
    vcard,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
