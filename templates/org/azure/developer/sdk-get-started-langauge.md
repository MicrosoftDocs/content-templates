---
title: #Required; Get started with Azure [service] [language] client libraries
description: #Required; Keep the description within 100- and 165-characters including spaces. Article description that is displayed in search results. Include the words "SDK Dev Guide", "client libraries", and the language to provide more details about the area covered. 
author: #Required; your GitHub user alias, with correct capitalization
ms.author: #Required; microsoft alias of author
ms.service: #Required; use the name-string related to slug in ms.product/ms.service
ms.topic: get-started #Required; leave this attribute/value as-is
ms.devlang: #Required; language per approved list. Language slug assigned to your language by ACOM.
ms.date: #Required; mm/dd/yyyy format

#CustomerIntent: As a < type of user >, I want < what? > so that < why? >.
---

# Get started with Azure [service] [language] client libraries

<!-- 

Issues to address in this template: 

1) How to provide a template when the SDK is more specific than just a language such as frontend/backend or mobile/desktop, or React (frontend frameworks). 

-->

<!-- Remove all the comments in this template before you #sign-off or merge to the main branch.

This template provides the basic structure of a SDK Dev Guide [Language]Getting Started pattern. See the
[instructions - Get started](dev-guide-sdk-instructions.md) in the pattern library.

You can provide feedback about this template at: https://aka.ms/patterns-feedback


--------------------------------------------------------------------------------------------------

<!-- 1. H1 ------------------------------------------------------------------------------
Required. Write an H1 that clearly conveys what the Get started article is for.

-->

# Get started with Azure [service] [optional - subservice] [language] client libraries 

<!-- ISSUE: This is wordy for SEO and no other reason. Take to SEO board for recommendations.-->

As you build applications to work with data resources in [service] in [language], your code primarily interacts with these resource types: [service or subservice name] accounts, [list of data plane objects]. This article explains these resource types and shows how they relate to one another. It also shows how application code uses the [service] [language] client libraries to interact with these various resources.

## Prerequisites <!-- ISSUE: is there a better developer-focused term? -->

## Set up your project

This section walks you through preparing a project to work with the Azure [service] client library for [language].

1. Create a project directory in your development environment. 

    From your project directory, install packages for the [package(s) for language] client libraries using the [package installer for language] command. 
    
    Examples for Python:
    
    ```bash
    pip install azure-storage-blob azure-identity
    ```

1. Create a code file, [language specific default file].[language specific extension]
1. Open the file in [default language IDE] and add the necessary statements to include the client libraries. 

    In this example, we add the following to our *.py* file:
    
    ```python
    from azure.identity import DefaultAzureCredential
    from azure.storage.blob import BlobServiceClient, BlobClient, ContainerClient
    ```

[package] client library information:
- [package](): Contains the primary classes (_client objects_) that you can use to operate on the [list of service objects mentioned in language agnostic Get Started article].

## Authorize access and connect with [package]

To connect your application to [service], create an instance of the [XClient <!-- top level object -->]([link to reference for object]) class. This object is your starting point to interact with data resources at the [service] account level. You can use it to operate on the [service] account and its [object list]. You can also use the service client to create [top object] clients or [lower-level] clients, depending on the resource you need to work with.

To learn more about creating and managing client objects, see [Connect with ...]().

You can authorize a `XClient` object by using an [authentication mechanism list]


## [Passwordless (Recommended)](#tab/azure-ad)
## [SAS token](#tab/sas-token)
## [Account key](#tab/account-key)

## Build your application

As you build applications to work with data resources in [service], your code primarily interacts with three resource types: [conceptual objects identified in object model]. To learn more about these resource types, how they relate to one another, and how apps interact with resources, see [Get started]().

The following guides show you how to work with data resources and perform specific actions using the [service] client library for language:


| Guide | Description |
|--|---|
| [Task action name]() | [Task action description] |

```