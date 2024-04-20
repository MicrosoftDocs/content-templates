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

# Authorize access from your application using <authentication name> with <language>

<!-- Example H1: 

Authorize access from your application using passwordless connections with .NET
>

<!-- Remove all the comments in this template before you #sign-off or merge to the main branch.
You can provide feedback about this template at: https://aka.ms/patterns-feedback
-->



<!-- 1. H1 ------------------------------------------------------------------------------
Required. The H1 can use the same text as the title, but it can be longer than 65 characters.

Example: # Authorize access from your application using .NET
-->

TODO: Add your heading

<!-- 2. Introductory paragraph ----------------------------------------------------------

Required. Lead with an intro that describes the Azure SDKs and how client objects connect an app to data resources. Keep it focused.

* Introduction immediately follows the H1 text.
* Introduction section should be 1 paragraph.
* Don't use a bulleted list of article H2 sections.

Example: 

The Azure SDK for JavaScript provides a seamless way to connect your application to Azure Blob Storage without the need for passwords. This is achieved using the DefaultAzureCredential object, which is part of the @azure/identity library. This object provides a simple, flexible, and secure method of authenticating your application. It attempts to use multiple authentication methods, falling back to the next one if the previous method fails. This allows your application to connect to Azure Blob Storage in a variety of environments without the need for explicit credentials. This guide will walk you through the process of setting up passwordless connections to Azure Blob Storage using the DefaultAzureCredential in the Azure SDK for JavaScript.

-->

TODO: Add your introductory paragraph

<!-- Include the authentication method's diagram - this is provided by the SDK's package README. Include the image from a shared resource instead of copying the image into your repo. 
-->

TODO: Add the authentication method's diagram



## About <authentication name>

<!--

Add an H2 to describe the authentication method and how it works. This doesn't have to be a long section, but it should provide a brief overview of the authentication method and how it works. Include links to the authentication method's documentation such as Azure Entra ID. 



-->

## Best practices for using <authentication name> with <language>

<!--

The section should include best practices for using the authentication method with the Azure SDK for the specified language.

The Azure SDK team for the language + service should be able to provide guidance on best practices for using the authentication method with the Azure SDK for the specified language.

-->

TODO: Add your best practices section

## Add required dependencies to <authenticaiton name> to your application

<!-- 

Include the following: 

* Explain how to add the required dependencies to your application.
* Show CLI commands to install the required packages if this is idiomatic of the language.
* Provide code snippets that show how to add the required dependencies to your application.

-->

## Add environment variables to support <authentication name> for your application

<!--

This section is optional. Include it if your authentication method requires environment variables to be set.

If the authentication method requires environment variables with a specific name, provide the names and values that need to be set.

If the environment variable names are required, use names which are idoimatice to the language. For example: 

AZURE_COSMOS_CONNECTION_STRING.

Provide code snippets that show how to set the environment variables in your application.

-->

TODO: Add your environment variables section

<!-- The remaining sections depend on the authentication mechanism. Only include if they are relevant to the authentication method. 
-->

## Application code boilerplate for <authentication name>

<!--

This section should have the minimal applicaiton code required to demonstrate the authentication method for a complete app. This allows the user to copy and use to quickly get started with the authentication method.

-->

TODO: Add your application code boilerplate section

## Use <Service> with <authentication name>

<!-- 

This seciton should explain how to use the authentication mechanism to create the top-level client object for the service. 

The code should include any best practices for failures and retries, and should be idiomatic to the language.

-->

TODO: Add your use <Service> with <authentication name> section