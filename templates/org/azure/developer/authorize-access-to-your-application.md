---
title: #Required
description: #Required; Keep the description within 100- and 165-characters including spaces. Article description that is displayed in search results. Include the word groups "SDK Dev Guide", "client libraries", "authorize access" and provide more details about the area covered.
author: #Required; your GitHub user alias, with correct capitalization
ms.author: #Required; microsoft alias of author
ms.service: #Required; use the name-string related to slug in ms.product/ms.service
ms.topic: how-to-conceptual #Required; leave this attribute/value as-is
ms.date: #Required; mm/dd/yyyy format

#CustomerIntent: As a < type of user >, I want < what? > so that < why? >.
---

# Authorize access to Azure [service] using [authentication name] with [language]

<!-- Remove all the comments in this template before you #sign-off or merge to the main branch.
You can provide feedback about this template at: https://aka.ms/patterns-feedback

This template provides the basic structure of a SDK Dev Guide [Language]Authorize access t your application pattern. See the
[instructions - Authorize access to you application](dev-guide-sdk-instructions.md) in the pattern library.

You can provide feedback about this template at: https://aka.ms/patterns-feedback

-->

<!-- 1. H1 ------------------------------------------------------------------------------
Required. The H1 can use the same text as the title, but it can be longer than 65 characters.

Example: # Authorize access from your application using .NET
-->

As you build applications in [language] to work with data resources in [service], your code needs access to the Azure service. This article explains the authorization types and shows how your application code gains access to the [service] with the client libraries.


<!-- Include the authentication method's diagram - this is provided by the SDK's package README. Include the image from a shared resource instead of copying the image into your repo. 
-->

TODO: Add the authentication method's diagram


## About [authentication name]

<!--

Add an H2 to describe the authentication method and how it works. This doesn't have to be a long section, but it should provide a brief overview of the authentication method and how it works. Include links to the authentication method's documentation such as Azure Entra ID. 
-->

## Best practices for using [authentication name] with [language]

<!--

The section should include best practices for using the authentication method with the Azure SDK for the specified language.

The Azure SDK team for the language + service should be able to provide guidance on best practices for using the authentication method in the language with the Azure SDK for the specified language.

-->

TODO: Add your best practices section

## Add required dependencies to [authenticaiton name] to your application

<!-- 

Include the following: 

* Explain how to add the required dependencies to your application.
* Show CLI commands to install the required packages if this is idiomatic of the language.
* Provide code snippets that show how to add the required dependencies to your application.

-->

<!--.NET---------------------->

```console
dotnet add package Azure.Identity
```

```dotnet 
use Azure.Identity;
```

<!--Java---------------------->

```xml (Java Maven)
<dependency>
  <groupId>com.azure</groupId>
  <artifactId>azure-identity</artifactId>
  <version>1.0.0</version>
</dependency>
```

```java
import com.azure.identity.DefaultAzureCredential;
```
<!--Python---------------------->

```console
pip install azure-identity
```

```python
from azure.identity import DefaultAzureCredential
```

<!--JavaScript/TypeScript---------------------->

```console
npm install @azure/identity
```

```javascript (ESM)
import { DefaultAzureCredential } from "@azure/identity";
```
<!--Go---------------------->

```console
go get github.com/Azure/azure-sdk-for-go/sdk/identity/armidentity
```

```go
import "github.com/Azure/azure-sdk-for-go/sdk/identity/armidentity"
```

## Add environment variables to support [authentication name] for your application

<!--

This section is optional. Include it if your authentication method requires environment variables to be set. Link to information on how to generate the values needed in the environment variables.

If the authentication method requires environment variables with a specific name, provide the names and values that need to be set.

AZURE_CLIENT_ID
AZURE_CLIENT_SECRET
AZURE_TENANT_ID

If the environment variable names are required but specific names are not required, use names which are idoimatice to the language. For example: 

AZURE_COSMOS_CONNECTION_STRING

Provide code snippets that show how to set the environment variables in your application.

-->


# [macOS](#tab/macos)

```bash
export NAME=VALUE
```

# [Linux](#tab/linux)

```bash
export NAME=value
```

# [Windows](#tab/windows)

```cmd
set NAME=value

```

---


<!-- The remaining sections depend on the authentication mechanism. Only include if they are relevant to the authentication method. 
-->

## Application code boilerplate for [authentication name]

<!--

This section should have the minimal application code required to demonstrate the authentication method for a complete app. This allows the user to copy and use to quickly get started with the authentication method.

TBD [Dina/Paul]: Library of sample code snippets for each language for boilerplate code.

-->

TODO: Add your application code boilerplate section

## Use [Service] with [authentication name]

<!-- 

This seciton should explain how to use the authentication mechanism to create the top-level client object for the service. 

The code should include any best practices for failures and retries, and should be idiomatic to the language.

TBD [Dina/Paul]: Library of sample code snippets for each language that show how to use the authentication method to create the top-level client object for the service.
-->

TODO: Add your use [Service] with [authentication name] section