# AcceptedGiftTypes

This object describes the types of gifts that can be gifted to a user or a chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**unlimited_gifts** | **boolean** | True, if unlimited regular gifts are accepted | [default to undefined]
**limited_gifts** | **boolean** | True, if limited regular gifts are accepted | [default to undefined]
**unique_gifts** | **boolean** | True, if unique gifts or gifts that can be upgraded to unique for free are accepted | [default to undefined]
**premium_subscription** | **boolean** | True, if a Telegram Premium subscription is accepted | [default to undefined]

## Example

```typescript
import { AcceptedGiftTypes } from 'tele_rest';

const instance: AcceptedGiftTypes = {
    unlimited_gifts,
    limited_gifts,
    unique_gifts,
    premium_subscription,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
