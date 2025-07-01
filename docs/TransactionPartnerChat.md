# TransactionPartnerChat

Describes a transaction with a chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Type of the transaction partner, always “chat” | [default to 'chat']
**chat** | [**Chat**](Chat.md) |  | [default to undefined]
**gift** | [**Gift**](Gift.md) |  | [optional] [default to undefined]

## Example

```typescript
import { TransactionPartnerChat } from 'tele_rest';

const instance: TransactionPartnerChat = {
    type,
    chat,
    gift,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
