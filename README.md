# ![LOGO](logo.png) MonitorManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the MonitorManagementClient API (version 2015-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/monitor-autoscale_API/2015-04-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:02+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists the autoscale settings for a subscription

*Tags:* `AutoscaleSettings`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

### Lists the autoscale settings for a resource group

*Tags:* `AutoscaleSettings`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

### Deletes and autoscale setting

*Tags:* `AutoscaleSettings`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `autoscaleSettingName` - _required_ - The autoscale setting name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

### Gets an autoscale setting

*Tags:* `AutoscaleSettings`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `autoscaleSettingName` - _required_ - The autoscale setting name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

### Updates an existing AutoscaleSettingsResource. To update other fields use the CreateOrUpdate method.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `autoscaleSettingName` - _required_ - The autoscale setting name.
* `api-version` - _required_ - Client Api Version.

### Creates or updates an autoscale setting.

*Tags:* `AutoscaleSettings`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `autoscaleSettingName` - _required_ - The autoscale setting name.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

## License

**flow**ground :- Telekom iPaaS / azure-com-monitor-autoscale-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
