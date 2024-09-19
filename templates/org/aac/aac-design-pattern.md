---
title: <Replace this text based on the guidance located in Completing the metadata under the Article title section.>   
description: <Replace this text based on the guidance located in Completing the metadata under the Article title section.>
keywords: <Replace this text based on the guidance located in Completing the metadata under the Article title section.>
ms.date: <Date of publish or major update, in mm/dd/yyyy format>
ms.topic: design-pattern
ms.service: azure-architecture-center
ms.subservice: design-pattern
pnp.series.title: Cloud Design Patterns
pnp.pattern.categories: <Replace this text based on the guidance located in Completing the metadata under the Article title section.>
---

# Article title
<!--
- This template is specific to Cloud Design Patterns. 
- Don't start the article with an alert.
- Ensure that your article only contains one H1 heading (#), which is the article title. The H1 heading is always followed by a short descriptive paragraph that describes what the article is about and how it can help the reader.
- Describe the problem that the pattern addresses, identify considerations for how to apply the pattern, and provide an example based on Microsoft Azure. Most of the patterns include code samples or snippets that show how to implement the pattern on Azure.
- Group the content into six subheadings. These subheadings are **Context and problem**, **Solution**, **Issues and considerations**, **When to use this pattern**, **Workload design**, **Example**, and **Next steps**. The H2 headings (##) and descriptions are included in this template. If you need to create a new heading under one of the H2 headings, use an H3 heading (###).
- Complete the metadata section at the top of this template. Update the placeholder text based on the following guidance:
  - **title:** Use the H1 title of your article from the top of this section. Make both titles identical. Maximum recommended character length is 60 characters.
  - **description:** Provide a brief summary of your article. This is the description that appears in search engine results, so ensure that the summary is clear, concise, and attracts your intended audience. Recommended character count is 150-160 characters.
  - **keywords:** Add a comma-separated list of key concepts and terms from your article. These are the words that your intended audience will submit in a search engine.
  - **ms.date:** Enter the date in mm/dd/yyyy format, as shown in the metadata field. Initially, this should be the date your article is published. After publication, refresh this field whenever the article is updated so that readers can see that the content is fresh.
  - **pnp.series.title:** Use Cloud Design Patterns for the patterns and practices series title. Don't change it.
  - **pnp.pattern.categories:** Review the following bracketed list and delete all categories that don't apply to your article. Then copy and paste the final bracketed list into the metadata section: 
    - [availability, data-management, design-implementation, messaging, management-monitoring, performance-scalability, resiliency, security].
-->

## Context and problem
<!--Provide a brief background on the specific pattern and the problem that the pattern addresses.-->

## Solution
<!--
- Describe the solution for the problem described in the **Context and problem** section. If there are multiple solutions, list them in order of complexity and provide instructions on how the reader can choose the best solution for their problem. 
- Provide a step-by-step approach to implement the solution and include screenshots to help guide the reader.
-->

## Issues and considerations

Consider the following points when deciding how to implement this pattern:

<!-- 
- Add a bulleted list of topics for the reader to consider before they implement the given solution.
- Emphasize concerns relevant to implementing the solution described in the previous section.
-->

## When to use this pattern

Use this pattern when:

<!--Add a bulleted-list of items that describe when this pattern should be used to help the reader determine if the solution is applicable to their scenario.-->

This pattern might not be suitable:

<!--Add a bulleted-list of items that describe when this pattern shouldn't be used to help the reader determine if the solution is applicable to their scenario.-->

## Workload design

An architect should evaluate how they can use <!--insert name of pattern here--> in their workload's design to address the goals and principles covered in the [Azure Well-Architected Framework pillars](/azure/well-architected/pillars). For example:

<!--
- Include only the rows that are relevant in the following table. This list is a pivot of the data on the design patterns lists in the Well-Architected Framework, so the two lists must be identical. 
- Don't add something here that isn't also in the Well-Architected Framework pillars. 
- Update the italicized content in the table as needed.
-->

| Pillar | How this pattern supports pillar goals |
| :----- | :------------------------------------- |
| [Reliability](/azure/well-architected/reliability/checklist) design decisions help your workload become **resilient** to malfunction and ensures that it **recovers** to a fully functioning state after a failure occurs. | _Explain how this pattern supports the stated goal of the pillar. Ideally, this should use practically the same text as found on <https://learn.microsoft.com/azure/well-architected/reliability/design-patterns>.<br/><br/> - [RE:nm Relevant guide name]()<br/> - [RE:nn Relevant guide name]() |
| [Security](/azure/well-architected/security/checklist) design decisions help ensure the **confidentiality**, **integrity**, and **availability** of your workload's data and systems. | _Explain how this pattern supports the stated goal of the pillar. Ideally, this should use practically the same text as found on <https://learn.microsoft.com/azure/well-architected/security/design-patterns>.<br/><br/> - [SE:nm Relevant guide name]()<br/> - [SE:nn Relevant guide name]() |
| [Cost optimization](/azure/well-architected/cost-optimization/checklist) focuses on **sustaining and improving** your workload's **return on investment**. | _Explain how this pattern supports the stated goal of the pillar. Ideally, this should use practically the same text as found on <https://learn.microsoft.com/azure/well-architected/cost-optimization/design-patterns>.<br/><br/> - [CO:nm Relevant guide name]()<br/> - [CO:nn Relevant guide name]() |
| [Operational excellence](/azure/well-architected/operational-excellence/checklist) helps deliver **workload quality** through **standardized processes** and team cohesion. | _Explain how this pattern supports the stated goal of the pillar. Ideally, this should use practically the same text as found on <https://learn.microsoft.com/azure/well-architected/operational-excellence/design-patterns>.<br/><br/> - [OE:nm Relevant guide name]()<br/> - [OE:nn Relevant guide name]() |
| [Performance efficiency](/azure/well-architected/performance-efficiency/checklist) helps your workload **efficiently meet demands** through optimizations in scaling, data, and code. | _Explain how this pattern supports the stated goal of the pillar. Ideally, this should use practically the same text as found on <https://learn.microsoft.com/azure/well-architected/performance-efficiency/design-patterns>.<br/><br/> - [PE:nm Relevant guide name]()<br/> - [PE:nn Relevant guide name]() |

Consider any tradeoffs against the goals of the other pillars that this pattern might introduce.

## Example
<!--Include a working sample that shows the reader how the pattern solution is used in a real-world situation. The sample should be specific and provide code snippets when appropriate.-->

## Next steps

The following information might be relevant when you implement this pattern:

<!--
- Add a bulleted list of links to third-party and other Learn and Microsoft topics. These topics can include links to pages that provide additional context or that might be useful in a next-steps context.
- Format Learn links to be site relative, such as (/azure/feature/article-name).
- Don't include locales such as `en-us` in links unless they don't work without it.
- Don't include a trailing slash in any links.
-->

## Related resources
<!--
- Add a bulleted list of related resource links.
- Use this section for architecture information that's relevant to the current article. It must be content that the Azure Architecture Center TOC refers to but can be from a repo other than the AAC repo.
- Ensure that links to articles in the AAC repo are repo-relative, such as (../../solution-ideas/articles/article-name.yml).
-->