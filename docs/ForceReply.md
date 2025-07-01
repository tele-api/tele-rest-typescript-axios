# ForceReply

Upon receiving a message with this object, Telegram clients will display a reply interface to the user (act as if the user has selected the bot\'s message and tapped \'Reply\'). This can be extremely useful if you want to create user-friendly step-by-step interfaces without having to sacrifice [privacy mode](https://core.telegram.org/bots/features#privacy-mode). Not supported in channels and for messages sent on behalf of a Telegram Business account.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**force_reply** | **boolean** | Shows reply interface to the user, as if they manually selected the bot\&#39;s message and tapped \&#39;Reply\&#39; | [default to true]
**input_field_placeholder** | **string** | *Optional*. The placeholder to be shown in the input field when the reply is active; 1-64 characters | [optional] [default to undefined]
**selective** | **boolean** | *Optional*. Use this parameter if you want to force reply from specific users only. Targets: 1) users that are @mentioned in the *text* of the [Message](https://core.telegram.org/bots/api/#message) object; 2) if the bot\&#39;s message is a reply to a message in the same chat and forum topic, sender of the original message. | [optional] [default to undefined]

## Example

```typescript
import { ForceReply } from 'tele_rest';

const instance: ForceReply = {
    force_reply,
    input_field_placeholder,
    selective,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
