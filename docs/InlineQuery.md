# InlineQuery

This object represents an incoming inline query. When the user sends an empty query, your bot could return some default or trending results.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this query | [default to undefined]
**from** | [**User**](User.md) |  | [default to undefined]
**query** | **string** | Text of the query (up to 256 characters) | [default to undefined]
**offset** | **string** | Offset of the results to be returned, can be controlled by the bot | [default to undefined]
**chat_type** | **string** | *Optional*. Type of the chat from which the inline query was sent. Can be either “sender” for a private chat with the inline query sender, “private”, “group”, “supergroup”, or “channel”. The chat type should be always known for requests sent from official clients and most third-party clients, unless the request was sent from a secret chat | [optional] [default to undefined]
**location** | [**Location**](Location.md) |  | [optional] [default to undefined]

## Example

```typescript
import { InlineQuery } from 'tele_rest';

const instance: InlineQuery = {
    id,
    from,
    query,
    offset,
    chat_type,
    location,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
