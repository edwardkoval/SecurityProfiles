# ApplicationSecurityState resource type

Complex type containing stateful information about the application

## Properties

| Property  | Type|Description|
|:---------------|:--------|:----------|
|deploymentPackageUrl|String|URI to deployment package and/or type of deployment package (e.g. appx, MSI, etc.)|
|name|String|Application name|
|permissionsRequired|String|The level of permissions the application requires to function. Possible values are: `unknown`, `anonymous`, `guest`, `user`, `administrator`, `system`.|
|publisher|String|The application publisher name. This helps distinguish between applications with the same AppX name|
|riskScore|String|Provider-generated/calculated risk score of the application|

## JSON representation

Here is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.ApplicationSecurityState"
}-->

```json
{
  "deploymentPackageUrl": "String",
  "name": "String",
  "permissionsRequired": "String",
  "publisher": "String",
  "riskScore": "String"
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "ApplicationSecurityState resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->