# ![LOGO](logo.png) CommerceManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the CommerceManagementClient API (version 2015-06-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-Commerce/2015-06-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:25+03:00

## API Description

The Admin Commerce Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns the list of supported REST operations.

*Tags:* `Commerce`

#### Input Parameters
* `api-version` - _required_ - Client API Version.

### Gets a collection of SubscriberUsageAggregates, which are UsageAggregates from users.

*Tags:* `Commerce`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.
* `reportedStartTime` - _required_ - The reported start time (inclusive).
* `reportedEndTime` - _required_ - The reported end time (exclusive).
* `aggregationGranularity` - _optional_ - The aggregation granularity.
* `subscriberId` - _optional_ - The tenant subscription identifier.
* `continuationToken` - _optional_ - The continuation token.

### Update the encryption.

*Tags:* `Commerce`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-commerce-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
