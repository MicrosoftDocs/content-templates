---   
                             
# For details about MAX content metadata requirements, see https://review.docs.microsoft.com/en-us/office-authoring-guide/metadata-for-max-content-on-dmc?branch=master

# REQUIRED METADATA

title: Article title goes here       # Very important for SEO. See https://aka.ms/seo-for-writers-cheat-sheet
author: YourGitHubUserName           # This is your GitHub alias, not your Microsoft alias
ms.author: YourMicrosoftAlias        # Your Microsoft alias without @microsoft.com
ms.date: mm/dd/yyyy                  # Use the format mm/dd/yyyy. IMPORTANT: Update manually when you modify a topic.
manager: YourManagersMicrosoftAlias  # Your manager's Microsoft alias without @microsoft.com
audience: ITPro                      # One of: Admin, ITPro, Developer
ms.topic: TypeOfTopic                # See metadata requirements link above for allowed values.
localization_priority: Normal        # See metadata requirements link above for allowed values.
ms.collection: some-scs-name         # See metadata requirements link above for allowed values.
# Choose EITHER ms.service OR ms.prod - NOT BOTH. Delete the one you don't use.
ms.service: ServiceID                # See metadata requirements link above for allowed values.
ms.prod: ProductID                   # See metadata requirements link above for allowed values.


# OPTIONAL METADATA

description:                         # Treat this like a summary tag in DxStudio. It helps with SEO.
ms.custom:                           # Similar to Set Free Tag. Use sparingly, limited character space.
ms.reviewer: MsAlias1, MsAlias2, etc # List contributors' Microsoft aliases, separated with commas.
robots:                              # Omit this field to make content searchable. Include it to hide from search.

---
# Landing from Message Center: Admin overview of feature

## FeatureName overview

Short overview of what the new feature is. 

- What is the new or updated experience. Include a screenshot (what does it look like?). 
    
- Is the feature on or off by default? 
    
- Where can they go to get more information? link to end user overview or landing page.
    
![Placeholder - maximum width for SOC article art is 520 pixels](images/)
  
## Set it up/Manage

### In Preview: **This feature** is in preview, how do I opt in? -OR- At GA or after: **This feature** is on by default for your organization.

To opt-in and use **this feature** while it's in preview, see **Setup tab**. -OR- To prevent your org or individuals from using this feature until you've reviewed it, you can remove the **feature** from the App launcher by following this article, [Prevent users from starting to use new features until my organization is ready](6f55cdae-078d-4834-86cc-fcef98ba74b8.md#Prevent). You can also make other changes such as [letting Microsoft know](6f55cdae-078d-4834-86cc-fcef98ba74b8.md#limits) when you want features to release to your tenant.

### How do I manage this feature or how do I set up this feature?

Cover these points: 

- Is this feature per org or per user? 
    
- Use PowerShell or UI?
    
- For Set up: short instructions on how to turn on the feature for the organization or for individual users. If you want to turn it off for individuals or your whole organization right away, see [How do I turn this feature on or off for my organization?](#Off)
    
- For Manage: sections with basic management tasks.
    
If there are more tasks, add links for where to find more help (like on a landing page?) 

## Security & Compliance

If your business has legal, regulatory, and technical standards to meet for content security and data use, this section is for you. 

### Where is the data associated with this feature stored?

Also include any other data implications.

### Does **insert feature/app name** meet our compliance requirements?

To help customers with their compliance needs related to Office 365, we have created a compliance framework that is designed to give customers visibility into Office 365’s compliance with global, regional and industry standards, and details how customers can control Office 365 services based on compliance needs. Review our [Office 365 Compliance Framework for Industry Standards and Regulations](http://go.microsoft.com/fwlink/p/?LinkId=615657) **insert feature/app name** is in.

## FAQ - Frequently-asked administrator questions about **feature**:

### Does this feature depend on any other features?

### List of dependent feature (e.g. Office Graph, Delve, etc….)

### What happens if I disable **dependent features, e.g. Graph**

Include details what experience will be if one or more of dependent features are disabled.

### Where can I find more controls and limits information?

Find your feature area in the service descriptions, and point to the specific content. starting point: [Office 365 Platform Service Description](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx)
