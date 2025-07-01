# InlineKeyboardMarkup

This object represents an [inline keyboard](https://core.telegram.org/bots/features#inline-keyboards) that appears right next to the message it belongs to.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inline_keyboard** | **Array&lt;Array&lt;InlineKeyboardButton&gt;&gt;** | Array of button rows, each represented by an Array of [InlineKeyboardButton](https://core.telegram.org/bots/api/#inlinekeyboardbutton) objects | [default to undefined]

## Example

```typescript
import { InlineKeyboardMarkup } from 'tele_rest';

const instance: InlineKeyboardMarkup = {
    inline_keyboard,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
