# ![LOGO](logo.png) Security Center **flow**ground Connector

## Description

A generated **flow**ground connector for the Security Center API (version 2017-08-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/security-advancedThreatProtectionSettings/2017-08-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:14:14+03:00

## API Description

API spec for Microsoft.Security (Azure Security Center) resource provider

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets the Advanced Threat Protection settings for the specified resource.

*Tags:* `AdvancedThreatProtection`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `resourceId` - _required_ - The identifier of the resource.
* `settingName` - _required_ - Advanced Threat Protection setting name.
    Possible values: current.

### Creates or updates the Advanced Threat Protection settings on a specified resource.

*Tags:* `AdvancedThreatProtection`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `resourceId` - _required_ - The identifier of the resource.
* `settingName` - _required_ - Advanced Threat Protection setting name.
    Possible values: current.

## License

**flow**ground :- Telekom iPaaS / azure-com-security-advanced-threat-protection-settings-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
