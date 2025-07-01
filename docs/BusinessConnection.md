# BusinessConnection

Describes the connection of the bot with a business account.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier of the business connection | [default to undefined]
**user** | [**User**](User.md) |  | [default to undefined]
**user_chat_id** | **number** | Identifier of a private chat with the user who created the business connection. This number may have more than 32 significant bits and some programming languages may have difficulty/silent defects in interpreting it. But it has at most 52 significant bits, so a 64-bit integer or double-precision float type are safe for storing this identifier. | [default to undefined]
**date** | **number** | Date the connection was established in Unix time | [default to undefined]
**is_enabled** | **boolean** | True, if the connection is active | [default to undefined]
**rights** | [**BusinessBotRights**](BusinessBotRights.md) |  | [optional] [default to undefined]

## Example

```typescript
import { BusinessConnection } from 'tele_rest';

const instance: BusinessConnection = {
    id,
    user,
    user_chat_id,
    date,
    is_enabled,
    rights,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
