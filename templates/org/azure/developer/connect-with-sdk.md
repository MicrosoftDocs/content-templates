---
title: #Required
description: #Required; Keep the description within 100- and 165-characters including spaces.
author: #Required; your GitHub user alias, with correct capitalization
ms.author: #Required; microsoft alias of author
ms.service: #Required; use the name-string related to slug in ms.product/ms.service
ms.topic: how-to #Required; leave this attribute/value as-is
ms.date: #Required; mm/dd/yyyy format

#CustomerIntent: As a < type of user >, I want < what? > so that < why? >.
---

# Connect with the SDK

<!-- Remove all the comments in this template before you #sign-off or merge to the main branch.
You can provide feedback about this template at: https://aka.ms/patterns-feedback
-->

<!-- 1. H1 ------------------------------------------------------------------------------
Required. The H1 can use the same text as the title, but it can be longer than 65 characters.

Example: # Create and manage client objects that interact with data resources
-->

TODO: Add your heading

<!-- 2. Introductory paragraph ----------------------------------------------------------

Required. Lead with an intro that describes the Azure SDKs and how client objects connect an app to data resources. Keep it focused.

* Introduction immediately follows the H1 text.
* Introduction section should be 1 paragraph.
* Don't use a bulleted list of article H2 sections.

Example: The Azure SDKs are collections of libraries built to make it easier to use Azure services from different languages. The SDKs are designed to simplify interactions between your application and Azure resources. Working with Azure resources using the SDK begins with creating a client instance. This article shows how to create client objects to interact with data resources in [service/subservice], and offers best practices on how to manage clients in your application.

-->

TODO: Add your introductory paragraph

<!-- 3. About client objects ----------------------------------------------------------------

Required. A section describing client objects should be the first H2 after the H1. 

## About client objects

* List the various data resource layers in a service
* Describe how client objects are the means by which an application connects to and interacts with these resources.
* Depending on the complexity of the service, the user may benefit from a table or list that displays the resource types in the service and links to the corresponding client library classes for each supported language SDK.
-->

## About client objects

TODO: Add your client object description

The Azure [service/subservice] client libraries allow you to interact with [n] types of resources in the [service]: 
- [resource 1]
- [resource n]

The following table shows the client classes that represent each resource type:

[Include a table or list that identifies the resource types and the corresponding client classes for each supported language SDK.]

<!-- 4. Client object authorization ---------------------------------------------------------

Required. The user should understand that authorization is necessary for an app to access and interact with data resources in a service.

* List the supported authorization mechanisms that are used to grant the appropriate level of access to a client object. For example, Azure AD, SAS, or shared key authorization.
* Typically, this section is nonprescriptive and links are provided to a separate authorization article that provide more detail and example.

-->

TODO: Add your client object authorization description

## Authorize a client object

The following authorization mechanisms can be used to grant the appropriate level of access to a client object:

- [Authorization mechanism 1]
- [Authorization mechanism n]

<!-- 5. Client object creation ---------------------------------------------------------

Required. The user should understand how to create client objects to work with data resources in a service.

* This section demonstrates client object creation using code examples for each supported language.
* The samples are narrowly focused on creating an authorized client object, as other functionality is covered elsewhere in the developer guide.
* This section typically alternates between explanatory text and code examples (as conceptual tabs for each language SDK).

-->

TODO: Add your client object creation examples

## Create a client object

Working with any Azure resource using the SDK begins with creating a client object. In this section, you learn how to create client objects to interact with the three types of resources in the [service]: [resource 1], ... [resource n].

### Create a [client class] object

[This section should be repeated to cover each resource level that can be represented by a client object.]

[Briefly describe the client class and the resource level it represents.]

The following code example shows how to create a [client class] object:

[Add code snippet for each SDK language (tabbed).]

<!-- 6. Client object management ---------------------------------------------------------

Optional. The user should understand best practices for client management throughout the app lifetime. 

* This section is focused on Azure SDK clients generally, and can include client immutability, thread safety, and recommendation of singleton clients.

-->

## Manage client objects

TODO: Add client object management information

```