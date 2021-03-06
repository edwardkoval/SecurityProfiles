# Use Microsoft Graph to integrate with the Intelligent Security Graph

 > **Important:** APIs under the /beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

The Microsoft Intelligent Security Graph is a unified platform for combatting cyberthreats. It powers real-time threat protection for Microsoft products and services and supports an ecosystem of integrated solutions.

The security API for the Microsoft Graph makes it easy to connect with and extend the Intelligent Security Graph. Leverage the Microsoft Graph to build security solutions that consolidate and correlate security alerts from multiple sources, unlock contextual data to inform investigations, and automate security operations for greater efficiency.

## Why connect to the Intelligent Security Graph?

By connecting with Microsoft and partner security solutions that are part of the Intelligent Security Graph, you can more readily realize and enrich the value of these solutions. Use the security API to:

### Unify and standardize alert management

Correlate alerts across security solutions more easily with a common alert schema, write code once to integrate alerts from any graph-supported security solution, and keep alert status and assignments in sync across all solutions. Also, stream alerts to Security Information and Event Management (SIEM) solutions such as Splunk and IBM QRadar via [Azure Monitor](https://blogs.msdn.microsoft.com/azuresecurity/2016/08/23/azure-log-siem-configuration-steps/).

### Federated security aggregation service

Queries submitted to the Microsoft Graph Security API are sent to all onboarded security providers and the aggregated responses are returned to the caller.

### Unlock security context to drive investigation

Dive deep into related security-relevant inventory (like users, hosts, apps, etc.) then add organizational context from other Microsoft Graph providers (Azure Active Directory, Microsoft Intune, Office 365, etc.) to bring business and security context together and improve threat response.

### Automate SecOps for greater efficiency (coming soon)

Build and execute investigation and remediation runbooks, automate security policy checks and rule enforcement, and orchestrate actions across security solutions.

## Authorization

For more information about permissions, including delegated and application permissions, see [Permissions](../../../concepts/permissions_reference.md).

## Common use cases

The following are some of the most popular requests for working with the security API:

| **Use cases**   | **REST resources** | **See also** |
|:---------------|:--------|:----------|
| Get Alerts | [Get alerts](../api/alert_list.md) | [https://graph.microsoft.com/beta/security/alerts](https://developer.microsoft.com/en-us/graph/graph-explorer?request=security/alerts&method=GET&version=testSecurity&GraphUrl=https://graph.microsoft.com) |
| Update Alerts | [Update alert](../api/alert_update.md) | `https://graph.microsoft.com/beta/security/alerts/{alert-id}` |
| Get Security Profiles | [Security Profiles](../resources/securityprofiles.md) | [https://graph.microsoft.com/beta/security/hostSecurityProfiles](https://developer.microsoft.com/en-us/graph/graph-explorer?request=security/hostSecurityProfiles&method=GET&version=testSecurity&GraphUrl=https://graph.microsoft.com) |

## Next steps

The security API can open up new ways for you to engage with security solutions from Microsoft and partners. Follow these steps to get started:

- Drill down into [alerts](../resources/alert.md) and [security profiles](../resources/securityprofiles.md).
- Try the API in the [Graph Explorer](https://developer.microsoft.com/graph/graph-explorer). In Graph Explorer, Select “show more samples” and turn “on” the Security category.

Need more ideas? See [how some of our partners are using Microsoft Graph](https://developer.microsoft.com/graph/graph/examples#partners).
