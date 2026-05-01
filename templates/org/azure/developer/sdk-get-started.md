---
title: #Required; Get started with Azure [service] client libraries
description: #Required; Keep the description within 100- and 165-characters including spaces. Article description that is displayed in search results. Include the words "SDK Dev Guide" and "client libraries" and provide more details about the area covered.
author: #Required; your GitHub user alias, with correct capitalization
ms.author: #Required; microsoft alias of author
ms.service: #Required; use the name-string related to slug in ms.product/ms.service
ms.topic: get-started #Required; leave this attribute/value as-is
ms.date: #Required; mm/dd/yyyy format

#CustomerIntent: As a < type of user >, I want < what? > so that < why? >.
---

# Get started with Azure [service] client libraries

<!-- Remove all the comments in this template before you #sign-off or merge to the main branch.

This template provides the basic structure of a SDK Dev Guide [Language]Getting Started pattern. See the
[instructions - Get started](dev-guide-sdk-instructions.md) in the pattern library.

You can provide feedback about this template at: https://aka.ms/patterns-feedback

-->

<!-- 1. H1 ------------------------------------------------------------------------------
Required. The H1 can use the same text as the title, but it can be longer than 65 characters.

-->

# Get started with Azure [service] client libraries

As you build applications to work with data resources in [service], your code primarily interacts with these resource types: [service or subservice name] accounts, [list of data plane objects]. This article explains these resource types and shows how they relate to one another. It also shows how application code uses the [service] client libraries to interact with these various resources.

## [service or subservice] resource types

The [service or subservice] client libraries allow you to interact with these types of resources in the [service] service:

- [service accounts](#service-accounts)
- [object 1](#object-1)
- [object 2](#object-2)

The following diagram shows the relationship between these resources:

:::image type="content" source="{source}" alt-text="{alt-text}":::

### [service or subservice] accounts

A [service or subservice ] account provides ...

### [Data plane object]

A [data plane object] is ...

## Work with data resources using the Azure SDK

The Azure SDKs contain libraries that build on top of the Azure REST API, allowing you to interact with REST API operations through familiar programming language paradigms. The SDKs are designed to simplify interactions between your application and Azure resources.

In the [service or subservice] client libraries, each resource type is represented by one or more associated classes. These classes provide operations to work with an [service] resource.


<!-- Programming language H3s

Required. At least 1 language is required for a first release.

-->
## [.NET](#tab/dotnet)


The following table lists the basic classes, along with a brief description:

| Class | Description |
| --- | --- |
| [AClient]() |  |
| [BClient]() |  |
| [CClient]() | 

The following package contains the classes used to work with Blob Storage data resources:

- [SDK package name](): description of package

## [Go](#tab/go)


The following table lists the basic classes, along with a brief description:

| Class | Description |
| --- | --- |
| [AClient]() |  |
| [BClient]() |  |
| [CClient]() | 

The following package contains the classes used to work with Blob Storage data resources:

- [SDK package name](): description of package

## [Java](#tab/java)


The following table lists the basic classes, along with a brief description:

| Class | Description |
| --- | --- |
| [AClient]() |  |
| [BClient]() |  |
| [CClient]() | 

The following package contains the classes used to work with Blob Storage data resources:

- [SDK package name](): description of package

## [JavaScript](#tab/javascript)


The following table lists the basic classes, along with a brief description:

| Class | Description |
| --- | --- |
| [AClient]() |  |
| [BClient]() |  |
| [CClient]() | 

The following package contains the classes used to work with Blob Storage data resources:

- [SDK package name](): description of package

## [Python](#tab/python)


The following table lists the basic classes, along with a brief description:

| Class | Description |
| --- | --- |
| [AClient]() |  |
| [BClient]() |  |
| [CClient]() | 

The following package contains the classes used to work with Blob Storage data resources:

- [SDK package name](): description of package

---

## Next steps

Working with Azure resources using the SDK begins with creating a client instance. To learn more about client object creation and management, see [Connect with SDK](dev-guide-sdk-connect-with-sdk.md).

```