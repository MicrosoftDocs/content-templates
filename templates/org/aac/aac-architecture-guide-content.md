---
title: <Article title, which becomes the title metadata>
description: <Write a 100-160 character description that ends with a period and ideally starts with a call to action. This becomes the browse card description.>
author: <Contributor's GitHub username>
ms.author: <Contributor's Microsoft alias>
ms.date: <Date of publish or last freshness pass, in mm/dd/yyyy format>
ms.topic: conceptual
ms.service: azure-architecture-center
ms.subservice: architecture-guide
products:
  - <Choose 1-5 products from the list at https://review.learn.microsoft.com/help/contribute/architecture-center/aac-browser-authoring#products>
  - <1-5 products>
  - <1-5 products>
categories:
  - <Choose at least one category from the list at https://review.learn.microsoft.com/help/contribute/architecture-center/aac-browser-authoring#azure-categories>
  - <There can be more than one category>
---

# H1 title

Other than the H2s listed below, there are no further content requirements for Architecture Guides, except to follow all Microsoft and Learn style and pull request criteria. Diagrams are not required for this content type, but if a diagram is included, it should have a Dataflow/Workflow section underneath the diagram to explain it. See the [Example workload template](sample-solution-templates) sections on Architecture and Dataflow for details.

The Architecture Guide template requires the following sections at the end of the article:
  
## Contributors

> (Expected, but this section is optional if all the contributors would prefer to not include it)

> Start with the explanation text (same for every article), in italics. This makes it clear that Microsoft takes responsibility for the article (not the one contributor). Then include the "Pricipal authors" list and the "Additional contributors" list (if there are additional contributors) (all in plain text, not italics or bold). Link each contributor's name to the person's LinkedIn profile. After the name, place a pipe symbol ("|") with spaces, and then enter the person's title. We don't include the person's company, MVP status, or links to additional profiles (to minimize edits/updates). (The profiles can be linked to from the person's LinkedIn page, and we hope to automate that on the platform in the future). 
> Implement this format:

*This article is maintained by Microsoft. It was originally written by the following contributors.*

Principal authors: > Only the primary authors. List them alphabetically, by last name. Use this format: Fname Lname. If the article gets rewritten, keep the original authors and add in the new one(s).

 * [Author 1 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"
 * [Author 2 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"
 * > Continue for each primary author (even if there are 10 of them).

Other contributors: > Include contributing (but not primary) authors, major editors (not minor edits), and technical reviewers. List them alphabetically, by last name. Use this format: Fname Lname. It's okay to add in newer contributors.

 * [Contributor 1 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"
 * [Contributor 2 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"

## Next steps

> Link to Learn articles. Could also be to appropriate sources outside of Learn, such as GitHub repos, third-party documentation, or an official technical blog post. 
> - Links shouldn't include en-us locale unless they don't work without it.
> - Learn links should be site-relative, for example (/azure/feature/article-name).
> - Don't include trailing slash in any links.
> Example:

- [Azure Machine Learning documentation](/azure/machine-learning)
- [What are Azure Cognitive Services?](/azure/cognitive-services/what-are-cognitive-services)

## Related resources

> Use "Related resources" for architecture information that's relevant to the current article. It must be content that the Azure Architecture Center TOC refers to, but may be from a repo other than the AAC repo.
> Links to articles in the AAC repo should be repo-relative, for example (../../solution-ideas/articles/article-name.yml).
> Here is an example section:

Fully deployable architectures:

- [Chatbot for hotel reservations](/azure/architecture/example-scenario/ai/commerce-chatbot)
- [Build an enterprise-grade conversational bot](/azure/architecture/reference-architectures/ai/conversational-bot)
- [Speech-to-text conversion](/azure/architecture/reference-architectures/ai/speech-ai-ingestion)