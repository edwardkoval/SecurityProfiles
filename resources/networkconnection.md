# NetworkConnection resource type

Complex type containing stateful information about the network connection related to the alert

## Properties

| Property   | Type|Description|
|:---------------|:--------|:----------|
|destinationAddress|String|Destination IP address (of the network connection) as a string|
|destinationPort|String|Destination port (of the network connection) as a string|
|protocol|String|Network protocol. Possible values are: `unknown`, `ip`, `icmp`, `igmp`, `ggp`, `ipv4`, `tcp`, `pup`, `udp`, `idp`, `ipv6`, `ipv6RoutingHeader`, `ipv6FragmentHeader`, `ipSecEncapsulatingSecurityPayload`, `ipSecAuthenticationHeader`, `icmpV6`, `ipv6NoNextHeader`, `ipv6DestinationOptions`, `nd`, `raw`, `ipx`, `spx`, `spxII`.|
|sourceAddress|String|Source (i.e. origin) IP address (of the network connection) as a string|
|sourcePort|String|Source (i.e. origin) IP port (of the network connection) as a string|
|uri|String|Network connection URI string|

## JSON representation

Here is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.NetworkConnection"
}-->

```json
{
  "destinationAddress": "String",
  "destinationPort": "String",
  "protocol": "String",
  "sourceAddress": "String",
  "sourcePort": "String",
  "uri": "String"
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "NetworkConnection resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->