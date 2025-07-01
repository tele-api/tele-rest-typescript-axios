# InlineQueryResultContact

Represents a contact with a phone number. By default, this contact will be sent by the user. Alternatively, you can use *input\\_message\\_content* to send a message with the specified content instead of the contact.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the result, must be *contact* | [default to 'contact']
**id** | **string** | Unique identifier for this result, 1-64 Bytes | [default to undefined]
**phone_number** | **string** | Contact\&#39;s phone number | [default to undefined]
**first_name** | **string** | Contact\&#39;s first name | [default to undefined]
**last_name** | **string** | *Optional*. Contact\&#39;s last name | [optional] [default to undefined]
**vcard** | **string** | *Optional*. Additional data about the contact in the form of a [vCard](https://en.wikipedia.org/wiki/VCard), 0-2048 bytes | [optional] [default to undefined]
**reply_markup** | [**InlineKeyboardMarkup**](InlineKeyboardMarkup.md) |  | [optional] [default to undefined]
**input_message_content** | [**InputMessageContent**](InputMessageContent.md) |  | [optional] [default to undefined]
**thumbnail_url** | **string** | *Optional*. Url of the thumbnail for the result | [optional] [default to undefined]
**thumbnail_width** | **number** | *Optional*. Thumbnail width | [optional] [default to undefined]
**thumbnail_height** | **number** | *Optional*. Thumbnail height | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultContact } from 'tele_rest';

const instance: InlineQueryResultContact = {
    type,
    id,
    phone_number,
    first_name,
    last_name,
    vcard,
    reply_markup,
    input_message_content,
    thumbnail_url,
    thumbnail_width,
    thumbnail_height,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
