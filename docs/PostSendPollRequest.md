# PostSendPollRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | [**PostSendMessageRequestChatId**](PostSendMessageRequestChatId.md) |  | [default to undefined]
**question** | **string** | Poll question, 1-300 characters | [default to undefined]
**_options** | [**Array&lt;InputPollOption&gt;**](InputPollOption.md) | A JSON-serialized list of 2-10 answer options | [default to undefined]
**business_connection_id** | **string** | Unique identifier of the business connection on behalf of which the message will be sent | [optional] [default to undefined]
**message_thread_id** | **number** | Unique identifier for the target message thread (topic) of the forum; for forum supergroups only | [optional] [default to undefined]
**question_parse_mode** | **string** | Mode for parsing entities in the question. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. Currently, only custom emoji entities are allowed | [optional] [default to undefined]
**question_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | A JSON-serialized list of special entities that appear in the poll question. It can be specified instead of *question\\_parse\\_mode* | [optional] [default to undefined]
**is_anonymous** | **boolean** | *True*, if the poll needs to be anonymous, defaults to *True* | [optional] [default to undefined]
**type** | **string** | Poll type, “quiz” or “regular”, defaults to “regular” | [optional] [default to undefined]
**allows_multiple_answers** | **boolean** | *True*, if the poll allows multiple answers, ignored for polls in quiz mode, defaults to *False* | [optional] [default to undefined]
**correct_option_id** | **number** | 0-based identifier of the correct answer option, required for polls in quiz mode | [optional] [default to undefined]
**explanation** | **string** | Text that is shown when a user chooses an incorrect answer or taps on the lamp icon in a quiz-style poll, 0-200 characters with at most 2 line feeds after entities parsing | [optional] [default to undefined]
**explanation_parse_mode** | **string** | Mode for parsing entities in the explanation. See [formatting options](https://core.telegram.org/bots/api/#formatting-options) for more details. | [optional] [default to undefined]
**explanation_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | A JSON-serialized list of special entities that appear in the poll explanation. It can be specified instead of *explanation\\_parse\\_mode* | [optional] [default to undefined]
**open_period** | **number** | Amount of time in seconds the poll will be active after creation, 5-600. Can\&#39;t be used together with *close\\_date*. | [optional] [default to undefined]
**close_date** | **number** | Point in time (Unix timestamp) when the poll will be automatically closed. Must be at least 5 and no more than 600 seconds in the future. Can\&#39;t be used together with *open\\_period*. | [optional] [default to undefined]
**is_closed** | **boolean** | Pass *True* if the poll needs to be immediately closed. This can be useful for poll preview. | [optional] [default to undefined]
**disable_notification** | **boolean** | Sends the message [silently](https://telegram.org/blog/channels-2-0#silent-messages). Users will receive a notification with no sound. | [optional] [default to undefined]
**protect_content** | **boolean** | Protects the contents of the sent message from forwarding and saving | [optional] [default to undefined]
**allow_paid_broadcast** | **boolean** | Pass *True* to allow up to 1000 messages per second, ignoring [broadcasting limits](https://core.telegram.org/bots/faq#how-can-i-message-all-of-my-bot-39s-subscribers-at-once) for a fee of 0.1 Telegram Stars per message. The relevant Stars will be withdrawn from the bot\&#39;s balance | [optional] [default to undefined]
**message_effect_id** | **string** | Unique identifier of the message effect to be added to the message; for private chats only | [optional] [default to undefined]
**reply_parameters** | [**ReplyParameters**](ReplyParameters.md) |  | [optional] [default to undefined]
**reply_markup** | [**PostSendMessageRequestReplyMarkup**](PostSendMessageRequestReplyMarkup.md) |  | [optional] [default to undefined]

## Example

```typescript
import { PostSendPollRequest } from 'tele_rest';

const instance: PostSendPollRequest = {
    chat_id,
    question,
    _options,
    business_connection_id,
    message_thread_id,
    question_parse_mode,
    question_entities,
    is_anonymous,
    type,
    allows_multiple_answers,
    correct_option_id,
    explanation,
    explanation_parse_mode,
    explanation_entities,
    open_period,
    close_date,
    is_closed,
    disable_notification,
    protect_content,
    allow_paid_broadcast,
    message_effect_id,
    reply_parameters,
    reply_markup,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
