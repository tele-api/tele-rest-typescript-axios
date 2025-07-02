# GetMyDefaultAdministratorRightsRequest

Request parameters for getMyDefaultAdministratorRights

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**for_channels** | **boolean** | Pass *True* to get default administrator rights of the bot in channels. Otherwise, default administrator rights of the bot for groups and supergroups will be returned. | [optional] [default to undefined]

## Example

```typescript
import { GetMyDefaultAdministratorRightsRequest } from 'tele_rest';

const instance: GetMyDefaultAdministratorRightsRequest = {
    for_channels,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
