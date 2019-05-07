# ![LOGO](logo.png) CustomerInsightsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the CustomerInsightsManagementClient API (version 2017-04-26).

Generated from: https://api.apis.guru/v2/specs/azure.com/customer-insights/2017-04-26/swagger.json<br/>
Generated at: 2019-05-07T17:37:55+03:00

## API Description

The Azure Customer Insights management API provides a RESTful set of web services that interact with Azure Customer Insights service to manage your resources. The API has entities that capture the relationship between an end user and the Azure Customer Insights service.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Customer Insights REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Gets all hubs in the specified subscription.

*Tags:* `Hubs`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the hubs in a resource group.

*Tags:* `Hubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the specified hub.

*Tags:* `Hubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets information about the specified hub.

*Tags:* `Hubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Updates a Hub.

*Tags:* `Hubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the Hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates a hub, or updates an existing hub.

*Tags:* `Hubs`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the Hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the authorization policies in a specified hub.

*Tags:* `AuthorizationPolicies`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets an authorization policy in the hub.

*Tags:* `AuthorizationPolicies`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `authorizationPolicyName` - _required_ - The name of the policy.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates an authorization policy or updates an existing authorization policy.

*Tags:* `AuthorizationPolicies`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `authorizationPolicyName` - _required_ - The name of the policy.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Regenerates the primary policy key of the specified authorization policy.

*Tags:* `AuthorizationPolicies`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `authorizationPolicyName` - _required_ - The name of the policy.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Regenerates the secondary policy key of the specified authorization policy.

*Tags:* `AuthorizationPolicies`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `authorizationPolicyName` - _required_ - The name of the policy.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the connectors in the specified hub.

*Tags:* `Connectors`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a connector in the hub.

*Tags:* `Connectors`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `connectorName` - _required_ - The name of the connector.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a connector in the hub.

*Tags:* `Connectors`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `connectorName` - _required_ - The name of the connector.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates a connector or updates an existing connector in the hub.

*Tags:* `Connectors`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `connectorName` - _required_ - The name of the connector.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the connector mappings in the specified connector.

*Tags:* `ConnectorMappings`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `connectorName` - _required_ - The name of the connector.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a connector mapping in the connector.

*Tags:* `ConnectorMappings`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `connectorName` - _required_ - The name of the connector.
* `mappingName` - _required_ - The name of the connector mapping.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a connector mapping in the connector.

*Tags:* `ConnectorMappings`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `connectorName` - _required_ - The name of the connector.
* `mappingName` - _required_ - The name of the connector mapping.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates a connector mapping or updates an existing connector mapping in the connector.

*Tags:* `ConnectorMappings`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `connectorName` - _required_ - The name of the connector.
* `mappingName` - _required_ - The name of the connector mapping.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets data image upload URL.

*Tags:* `Images`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets entity type (profile or interaction) image upload URL.

*Tags:* `Images`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all interactions in the hub.

*Tags:* `Interactions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `locale-code` - _optional_ - Locale of interaction to retrieve, default is en-us.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets information about the specified interaction.

*Tags:* `Interactions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `interactionName` - _required_ - The name of the interaction.
* `locale-code` - _optional_ - Locale of interaction to retrieve, default is en-us.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates an interaction or updates an existing interaction within a hub.

*Tags:* `Interactions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `interactionName` - _required_ - The name of the interaction.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Suggests relationships to create relationship links.

*Tags:* `Interactions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `interactionName` - _required_ - The name of the interaction.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the KPIs in the specified hub.

*Tags:* `Kpi`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a KPI in the hub.

*Tags:* `Kpi`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `kpiName` - _required_ - The name of the KPI.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a KPI in the hub.

*Tags:* `Kpi`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `kpiName` - _required_ - The name of the KPI.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates a KPI or updates an existing KPI in the hub.

*Tags:* `Kpi`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `kpiName` - _required_ - The name of the KPI.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Reprocesses the Kpi values of the specified KPI.

*Tags:* `Kpi`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `kpiName` - _required_ - The name of the KPI.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the links in the specified hub.

*Tags:* `Links`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a link in the hub.

*Tags:* `Links`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `linkName` - _required_ - The name of the link.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a link in the hub.

*Tags:* `Links`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `linkName` - _required_ - The name of the link.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates a link or updates an existing link in the hub.

*Tags:* `Links`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `linkName` - _required_ - The name of the link.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the predictions in the specified hub.

*Tags:* `Predictions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a Prediction in the hub.

*Tags:* `Predictions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `predictionName` - _required_ - The name of the Prediction.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a Prediction in the hub.

*Tags:* `Predictions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `predictionName` - _required_ - The name of the Prediction.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates a Prediction or updates an existing Prediction in the hub.

*Tags:* `Predictions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `predictionName` - _required_ - The name of the Prediction.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets model status of the prediction.

*Tags:* `Predictions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `predictionName` - _required_ - The name of the Prediction.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets training results.

*Tags:* `Predictions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `predictionName` - _required_ - The name of the Prediction.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates the model status of prediction.

*Tags:* `Predictions`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `predictionName` - _required_ - The name of the Prediction.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all profile in the hub.

*Tags:* `Profiles`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `locale-code` - _optional_ - Locale of profile to retrieve, default is en-us.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a profile within a hub

*Tags:* `Profiles`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `profileName` - _required_ - The name of the profile.
* `locale-code` - _optional_ - Locale of profile to retrieve, default is en-us.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets information about the specified profile.

*Tags:* `Profiles`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `profileName` - _required_ - The name of the profile.
* `locale-code` - _optional_ - Locale of profile to retrieve, default is en-us.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates a profile within a Hub, or updates an existing profile.

*Tags:* `Profiles`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `profileName` - _required_ - The name of the profile.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the KPIs that enrich the profile Type identified by the supplied name. Enrichment happens through participants of the Interaction on an Interaction KPI and through Relationships for Profile KPIs.

*Tags:* `Profiles`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `profileName` - _required_ - The name of the profile.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all relationship links in the hub.

*Tags:* `RelationshipLinks`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a relationship link within a hub.

*Tags:* `RelationshipLinks`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `relationshipLinkName` - _required_ - The name of the relationship.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets information about the specified relationship Link.

*Tags:* `RelationshipLinks`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `relationshipLinkName` - _required_ - The name of the relationship link.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates a relationship link or updates an existing relationship link within a hub.

*Tags:* `RelationshipLinks`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `relationshipLinkName` - _required_ - The name of the relationship link.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all relationships in the hub.

*Tags:* `Relationships`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a relationship within a hub.

*Tags:* `Relationships`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `relationshipName` - _required_ - The name of the relationship.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets information about the specified relationship.

*Tags:* `Relationships`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `relationshipName` - _required_ - The name of the relationship.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates a relationship or updates an existing relationship within a hub.

*Tags:* `Relationships`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `relationshipName` - _required_ - The name of the Relationship.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the role assignments for the specified hub.

*Tags:* `RoleAssignments`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the role assignment in the hub.

*Tags:* `RoleAssignments`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `assignmentName` - _required_ - The name of the role assignment.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets the role assignment in the hub.

*Tags:* `RoleAssignments`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `assignmentName` - _required_ - The name of the role assignment.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a role assignment in the hub.

*Tags:* `RoleAssignments`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `assignmentName` - _required_ - The assignment name
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the roles for the hub.

*Tags:* `Roles`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all available views for given user in the specified hub.

*Tags:* `Views`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `userId` - _required_ - The user ID. Use * to retrieve hub level views.

### Deletes a view in the specified hub.

*Tags:* `Views`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `viewName` - _required_ - The name of the view.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `userId` - _required_ - The user ID. Use * to retrieve hub level view.

### Gets a view in the hub.

*Tags:* `Views`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `viewName` - _required_ - The name of the view.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `userId` - _required_ - The user ID. Use * to retrieve hub level view.

### Creates a view or updates an existing view in the hub.

*Tags:* `Views`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `viewName` - _required_ - The name of the view.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all available widget types in the specified hub.

*Tags:* `WidgetTypes`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets a widget type in the specified hub.

*Tags:* `WidgetTypes`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `hubName` - _required_ - The name of the hub.
* `widgetTypeName` - _required_ - The name of the widget type.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-customer-insights-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
