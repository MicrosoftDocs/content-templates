<!-- Use the aac-browse-header.yml-->
<!--
- Match the H1 title to the title metadata. Don't enter it here, but as the **name** value in the corresponding YAML file.
- Add a brief introduction of no more than three sentences and formatted as a single paragraph.-->[**Deploy this scenario**.](#deploy-this-scenario)

## Architecture

![alt text.](./media/folder_name/architecture-diagram.png)

_Download a [Visio file](https://arch-center.azureedge.net/architecture.vsdx) that contains this architecture diagram. This file must be uploaded to `https://arch-center.azureedge.net/`_

### Workflow

<!--
- Title this section "Workflow" if data isn't in the scenario.
- Use a numbered list that describes the dataflow or workflow of each step in the solution. Use a bulleted list if there are no numbers in the diagram. Start from the user or external data source, and then follow the flow through the rest of the solution. The following section uses the previous diagram as an example and should be updated for your specific article. The following dataflow corresponds to the previous diagram:
-->

The following workflow (or dataflow) corresponds to the previous diagram:

- **Thing 1**. Explain what happens with the first technology in the diagram.

- **Thing 2**. Explain what happens with the second technology in the diagram.

### Components
<!-- 
- Add a bulleted list of components in the architecture. It includes all relevant Azure services and has links to the Well-Architected Framework service guide for the product. This is for lead generation (what business, marketing, and PG want). It helps drive revenue.
- Describe why each component is necessary and what it does.
- Link the name of the service via embedded link to the Azure Well-Architected service guide if it exists, or to the service's product page. Exclude the localization part of the URL, such as `en-us`.
- The following section contains example components but should be updated for your specific article.
-->

- Examples:
  - [Azure Cognitive Services Language Understanding](https://azure.microsoft.com/services/cognitive-services/language-understanding-intelligent-service)
  - [Azure Cognitive Services Speech Services](https://azure.microsoft.com/services/cognitive-services/speech-services)
  - [Azure SQL Database](https://azure.microsoft.com/services/sql-database)
  - [Azure Monitor](https://azure.microsoft.com/services/monitor): Application Insights is a feature of Azure Monitor.
  - [Resource Groups][resource-groups] is a logical container for Azure resources. We use resource groups to organize everything related to this project in the Azure console.

### Alternatives
<!-- 

- Use this section to talk about alternative Azure services or architectures that you might consider for this solution. 
- Include the reasons why you might choose these alternatives. Customers find this valuable because they want to know what other services or technologies they can use as part of this architecture.
> Describe alternative technologies that were considered and why they weren't used.
-->

## Scenario details
<!--
- Explain the business problem and why this scenario was built to solve it. 
- Answer the following questions:
  - What prompted them to solve the problem?
  - What services were used in building out this solution?
  - What does this example scenario show? What are the customer's goals?
  - What were the benefits of implementing the solution?
-->

### Potential use cases
<!--
- Describe any other use cases or industries where this would be a fit.
> Describe how similar or different they are to what's in the article.
-->

These other uses cases have similar design patterns:
<!--List example use cases.-->

## Recommendations

You can apply the following recommendations to most scenarios. Follow these recommendations unless you have a specific requirement that overrides them.

<!--Include considerations for how to deploy or configure the elements of this architecture.-->

## Considerations
<!--
- Include *all* of these H3 sub-sections for the Reference Architecture template: Reliability, Security, Cost optimization, Operational excellence, and Performance efficiency.
- REQUIRED STATEMENT: Include the following statement to introduce this section:
-->

These considerations implement the pillars of the Azure Well-Architected Framework, which are guiding tenets that you can use to improve the quality of a workload. For more information, see [Well-Architected Framework](/azure/architecture/framework).

<!--
- Describe any lessons learned from running this that would be helpful for new customers. 
- Describe what went wrong and what went right when building it out. 
- Describe how to manage, maintain, and monitor this long term.
-->

### Reliability
<!--REQUIRED STATEMENT: If you use this section, include the following statement:-->

Reliability ensures that your application can meet the commitments you make to your customers. For more information, see [Design review checklist for Reliability](/azure/well-architected/reliability/checklist).

<!--
- Include resiliency and availability considerations. They can also be H4 headers in this section, if you think that they should be separate.
- Describe any key resilience and reliability considerations that aren't typical.
-->

### Security
<!--REQUIRED STATEMENT: If you use this section, include the following statement:-->

Security provides assurances against deliberate attacks and the abuse of your valuable data and systems. For more information, see [Design review checklist for Security](/azure/well-architected/security/checklist).

<!--
- Include identity and data sovereignty considerations in this section.
- Describe any security considerations that aren't typical.
- Because security is important to our business, be sure to include your Azure security baseline assessment recommendations in this section. See https://aka.ms/AzureSecurityBaselines.
-->

### Cost optimization
<!--
- REQUIRED: This section is required. Cost is of the utmost importance to our customers.
- REQUIRED STATEMENT: Include the following statement to introduce the section:
-->

Cost optimization is about looking at ways to reduce unnecessary expenses and improve operational efficiencies. For more information, see [Design review checklist for Cost Optimization](/azure/well-architected/cost-optimization/checklist).

<!--
- Answer the following questions:
    - How much will this cost to run? Try to answer without using dollar amounts.
    - Are there ways I could save cost?
    - If it scales linearly, then should we break it down by cost or unit? If it doesn't scale linearly, why?
    - What components make up the cost?
    - How does scale affect the cost?
- Link to the pricing calculator (<https://azure.microsoft.com/pricing/calculator>). Include all the components in the architecture, even if they have a $0 or $1 usage.
- Include small, medium, or large configurations if it makes sense to. Describe what needs to be changed when you move to larger sizes.
-->

### Operational excellence
<!--REQUIRED STATEMENT: If you use this section, include the following statement:-->

Operational excellence covers the operations processes that deploy an application and keep it running in production. For more information, see [Design review checklist for Operational Excellence](/azure/well-architected/operational-excellence/checklist).

<!--
- Include DevOps, monitoring, and diagnostics considerations in this section.
- Describe how to think about operating this solution.
-->

### Performance efficiency
<!--REQUIRED STATEMENT: If you use this section, include the following statement:-->

Performance efficiency refers to the ability of your workload to scale efficiently to meet user demands. For more information, see [Design review checklist for Performance Efficiency](/azure/well-architected/performance-efficiency/checklist).

<!--
- Include scalability considerations in this section.
- Answer the following questions:
  - Are there any key performance considerations beyond the typical?
  - Are there any size considerations around this solution specifically?
  - What scale does this work at?  
  - At what point do things break or not make sense for this architecture?
-->

## Deploy this scenario
<!--
- REQUIRED: Reference Architectures require a deployment. If you can't provide a deployment, use the Example Workload template instead.
- Describe a step-by-step process for implementing the reference architecture solution. Add the solution to GitHub, provide a link by using the following boilerplate text, and explain how to roll out the solution.
-->

A deployment for a reference architecture that implements these recommendations and considerations is available on [GitHub](https://www.github.com/path-to-repo).

1. First step
2. Second step
3. Third step ...

## Contributors
<!--This section is expected but optional if all the contributors prefer not to include it.

1. Start with the explanation text in italics that's the same for every article. This makes it clear that Microsoft takes responsibility for the article and not a single contributor.

1. Include the list of "Principal authors" and the list of "Additional contributors," if there are any. Format in plain text, not italics or bold.

1. Link each contributor's name to the person's LinkedIn profile. 

1. Insert a pipe symbol ("|") with spaces after the name, and then enter the person's title. To minimize edits or updates, don't include the person's company, MVP status, or links to additional profiles. You can link profiles from the person's LinkedIn page. In the future, we aim to automate this process on the platform.
-->

*This article is maintained by Microsoft. It was originally written by the following contributors.*

Principal authors: <!--List only the primary authors. List them alphabetically and by last name. Use the *First-name Last-name* format. If the article is rewritten, keep the original authors and add the new ones. List each primary author, even if there are 10 of them. Update the following example text.-->

 - [Author 1 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"
 - [Author 2 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"

Other contributors: <!--Include the contributing authors, editors who make major content changes, and technical reviewers. List them alphabetically by last name. Use the *First-name Last-name* format. It's okay to add newer contributors.-->

 - [Contributor 1 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"
 - [Contributor 2 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"

## Next steps
<!--
- Add a bulleted list of links to third-party and other Learn and Microsoft topics. These topics can include links to pages that provide additional context or that might be useful in a next-steps context.
- Format Learn links to be site relative, such as (/azure/feature/article-name).
- Don't include locales such as `en-us` in links unless they don't work without it.
- Don't include a trailing slash in any links.
- Link to documentation that answers the following questions:
  - Where should I go next if I want to start building this?
  - Are there any relevant case studies or customers doing something similar?
  - Is there any other documentation that might be useful? 
  - Are there product documents that go into more detail on specific technologies that are not already linked?
- Update the following example links.
-->

Examples:
- [Azure Machine Learning documentation](/azure/machine-learning)
- [What are Azure Cognitive Services?](/azure/cognitive-services/what-are-cognitive-services)

## Related resources
<!--
- Add a bulleted list of related resource links.
- Use this section for architecture information that's relevant to the current article. It must be content that the Azure Architecture Center TOC refers to but can be from a repo other than the AAC repo.
- Ensure that links to articles in the AAC repo are repo-relative, such as (../../solution-ideas/articles/article-name.yml).
- Update the following example links.
-->

Fully deployable architectures:

- [Chatbot for hotel reservations](/azure/architecture/example-scenario/ai/commerce-chatbot)
- [Build an enterprise-grade conversational bot](/azure/architecture/reference-architectures/ai/conversational-bot)
- [Speech-to-text conversion](/azure/architecture/reference-architectures/ai/speech-ai-ingestion)