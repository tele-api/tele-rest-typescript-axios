# InlineKeyboardButton

This object represents one button of an inline keyboard. Exactly one of the optional fields must be used to specify type of the button.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **string** | Label text on the button | [default to undefined]
**url** | **string** | *Optional*. HTTP or tg:// URL to be opened when the button is pressed. Links &#x60;tg://user?id&#x3D;&lt;user_id&gt;&#x60; can be used to mention a user by their identifier without using a username, if this is allowed by their privacy settings. | [optional] [default to undefined]
**callback_data** | **string** | *Optional*. Data to be sent in a [callback query](https://core.telegram.org/bots/api/#callbackquery) to the bot when the button is pressed, 1-64 bytes | [optional] [default to undefined]
**web_app** | [**WebAppInfo**](WebAppInfo.md) |  | [optional] [default to undefined]
**login_url** | [**LoginUrl**](LoginUrl.md) |  | [optional] [default to undefined]
**switch_inline_query** | **string** | *Optional*. If set, pressing the button will prompt the user to select one of their chats, open that chat and insert the bot\&#39;s username and the specified inline query in the input field. May be empty, in which case just the bot\&#39;s username will be inserted. Not supported for messages sent on behalf of a Telegram Business account. | [optional] [default to undefined]
**switch_inline_query_current_chat** | **string** | *Optional*. If set, pressing the button will insert the bot\&#39;s username and the specified inline query in the current chat\&#39;s input field. May be empty, in which case only the bot\&#39;s username will be inserted.    This offers a quick way for the user to open your bot in inline mode in the same chat - good for selecting something from multiple options. Not supported in channels and for messages sent on behalf of a Telegram Business account. | [optional] [default to undefined]
**switch_inline_query_chosen_chat** | [**SwitchInlineQueryChosenChat**](SwitchInlineQueryChosenChat.md) |  | [optional] [default to undefined]
**copy_text** | [**CopyTextButton**](CopyTextButton.md) |  | [optional] [default to undefined]
**callback_game** | **any** |  | [optional] [default to undefined]
**pay** | **boolean** | *Optional*. Specify *True*, to send a [Pay button](https://core.telegram.org/bots/api/#payments). Substrings “⭐” and “XTR” in the buttons\&#39;s text will be replaced with a Telegram Star icon.    **NOTE:** This type of button **must** always be the first button in the first row and can only be used in invoice messages. | [optional] [default to undefined]

## Example

```typescript
import { InlineKeyboardButton } from 'tele_rest';

const instance: InlineKeyboardButton = {
    text,
    url,
    callback_data,
    web_app,
    login_url,
    switch_inline_query,
    switch_inline_query_current_chat,
    switch_inline_query_chosen_chat,
    copy_text,
    callback_game,
    pay,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
