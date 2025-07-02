# PostAnswerCallbackQueryRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**callback_query_id** | **string** | Unique identifier for the query to be answered | [default to undefined]
**text** | **string** | Text of the notification. If not specified, nothing will be shown to the user, 0-200 characters | [optional] [default to undefined]
**show_alert** | **boolean** | If *True*, an alert will be shown by the client instead of a notification at the top of the chat screen. Defaults to *false*. | [optional] [default to false]
**url** | **string** | URL that will be opened by the user\&#39;s client. If you have created a [Game](https://core.telegram.org/bots/api/#game) and accepted the conditions via [@BotFather](https://t.me/botfather), specify the URL that opens your game - note that this will only work if the query comes from a [*callback\\_game*](https://core.telegram.org/bots/api/#inlinekeyboardbutton) button.    Otherwise, you may use links like &#x60;t.me/your_bot?start&#x3D;XXXX&#x60; that open your bot with a parameter. | [optional] [default to undefined]
**cache_time** | **number** | The maximum amount of time in seconds that the result of the callback query may be cached client-side. Telegram apps will support caching starting in version 3.14. Defaults to 0. | [optional] [default to 0]

## Example

```typescript
import { PostAnswerCallbackQueryRequest } from 'tele_rest';

const instance: PostAnswerCallbackQueryRequest = {
    callback_query_id,
    text,
    show_alert,
    url,
    cache_time,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
