# SetMyDefaultAdministratorRightsPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rights** | [**ChatAdministratorRights**](ChatAdministratorRights.md) |  | [optional] [default to undefined]
**for_channels** | **boolean** | Pass *True* to change the default administrator rights of the bot in channels. Otherwise, the default administrator rights of the bot for groups and supergroups will be changed. | [optional] [default to undefined]

## Example

```typescript
import { SetMyDefaultAdministratorRightsPostRequest } from 'tele_rest';

const instance: SetMyDefaultAdministratorRightsPostRequest = {
    rights,
    for_channels,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
