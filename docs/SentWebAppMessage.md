# SentWebAppMessage

Describes an inline message sent by a [Web App](https://core.telegram.org/bots/webapps) on behalf of a user.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inline_message_id** | **string** | *Optional*. Identifier of the sent inline message. Available only if there is an [inline keyboard](https://core.telegram.org/bots/api/#inlinekeyboardmarkup) attached to the message. | [optional] [default to undefined]

## Example

```typescript
import { SentWebAppMessage } from 'tele_rest';

const instance: SentWebAppMessage = {
    inline_message_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
