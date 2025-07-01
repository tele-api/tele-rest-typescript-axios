# Poll

This object contains information about a poll.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique poll identifier | [default to undefined]
**question** | **string** | Poll question, 1-300 characters | [default to undefined]
**_options** | [**Array&lt;PollOption&gt;**](PollOption.md) | List of poll options | [default to undefined]
**total_voter_count** | **number** | Total number of users that voted in the poll | [default to undefined]
**is_closed** | **boolean** | *True*, if the poll is closed | [default to undefined]
**is_anonymous** | **boolean** | *True*, if the poll is anonymous | [default to undefined]
**type** | **string** | Poll type, currently can be “regular” or “quiz” | [default to undefined]
**allows_multiple_answers** | **boolean** | *True*, if the poll allows multiple answers | [default to undefined]
**question_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. Special entities that appear in the *question*. Currently, only custom emoji entities are allowed in poll questions | [optional] [default to undefined]
**correct_option_id** | **number** | *Optional*. 0-based identifier of the correct answer option. Available only for polls in the quiz mode, which are closed, or was sent (not forwarded) by the bot or to the private chat with the bot. | [optional] [default to undefined]
**explanation** | **string** | *Optional*. Text that is shown when a user chooses an incorrect answer or taps on the lamp icon in a quiz-style poll, 0-200 characters | [optional] [default to undefined]
**explanation_entities** | [**Array&lt;MessageEntity&gt;**](MessageEntity.md) | *Optional*. Special entities like usernames, URLs, bot commands, etc. that appear in the *explanation* | [optional] [default to undefined]
**open_period** | **number** | *Optional*. Amount of time in seconds the poll will be active after creation | [optional] [default to undefined]
**close_date** | **number** | *Optional*. Point in time (Unix timestamp) when the poll will be automatically closed | [optional] [default to undefined]

## Example

```typescript
import { Poll } from 'tele_rest';

const instance: Poll = {
    id,
    question,
    _options,
    total_voter_count,
    is_closed,
    is_anonymous,
    type,
    allows_multiple_answers,
    question_entities,
    correct_option_id,
    explanation,
    explanation_entities,
    open_period,
    close_date,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
