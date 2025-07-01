# WriteAccessAllowed

This object represents a service message about a user allowing a bot to write messages after adding it to the attachment menu, launching a Web App from a link, or accepting an explicit request from a Web App sent by the method [requestWriteAccess](https://core.telegram.org/bots/webapps#initializing-mini-apps).

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**from_request** | **boolean** | *Optional*. True, if the access was granted after the user accepted an explicit request from a Web App sent by the method [requestWriteAccess](https://core.telegram.org/bots/webapps#initializing-mini-apps) | [optional] [default to undefined]
**web_app_name** | **string** | *Optional*. Name of the Web App, if the access was granted when the Web App was launched from a link | [optional] [default to undefined]
**from_attachment_menu** | **boolean** | *Optional*. True, if the access was granted when the bot was added to the attachment or side menu | [optional] [default to undefined]

## Example

```typescript
import { WriteAccessAllowed } from 'tele_rest';

const instance: WriteAccessAllowed = {
    from_request,
    web_app_name,
    from_attachment_menu,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
