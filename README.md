# ![LOGO](logo.png) Visual Studio Projects Resource Provider Client **flow**ground Connector

## Description

A generated **flow**ground connector for the Visual Studio Projects Resource Provider Client API (version 2018-08-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/visualstudio-PipelineTemplates/2018-08-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:14:33+03:00

## API Description

Use these APIs to manage Visual Studio Team Services resources through the Azure Resource Manager. All task operations conform to the HTTP/1.1 protocol specification and each operation returns an x-ms-request-id header that can be used to obtain information about the request. You must make sure that requests made to these resources are secure. For more information, see https://docs.microsoft.com/en-us/rest/api/index.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### PipelineTemplates_List

> Gets all pipeline templates which can be used to configure a CI/CD pipeline in a new or an existing Team Services project.

*Tags:* `PipelineTemplates`

#### Input Parameters
* `api-version` - _required_ - API Version

## License

**flow**ground :- Telekom iPaaS / azure-com-visualstudio-pipeline-templates-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
