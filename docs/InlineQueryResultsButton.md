# InlineQueryResultsButton

This object represents a button to be shown above inline query results. You **must** use exactly one of the optional fields.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **string** | Label text on the button | [default to undefined]
**web_app** | [**WebAppInfo**](WebAppInfo.md) |  | [optional] [default to undefined]
**start_parameter** | **string** | *Optional*. [Deep-linking](https://core.telegram.org/bots/features#deep-linking) parameter for the /start message sent to the bot when a user presses the button. 1-64 characters, only &#x60;A-Z&#x60;, &#x60;a-z&#x60;, &#x60;0-9&#x60;, &#x60;_&#x60; and &#x60;-&#x60; are allowed.    *Example:* An inline bot that sends YouTube videos can ask the user to connect the bot to their YouTube account to adapt search results accordingly. To do this, it displays a \&#39;Connect your YouTube account\&#39; button above the results, or even before showing any. The user presses the button, switches to a private chat with the bot and, in doing so, passes a start parameter that instructs the bot to return an OAuth link. Once done, the bot can offer a [*switch\\_inline*](https://core.telegram.org/bots/api/#inlinekeyboardmarkup) button so that the user can easily return to the chat where they wanted to use the bot\&#39;s inline capabilities. | [optional] [default to undefined]

## Example

```typescript
import { InlineQueryResultsButton } from 'tele_rest';

const instance: InlineQueryResultsButton = {
    text,
    web_app,
    start_parameter,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
