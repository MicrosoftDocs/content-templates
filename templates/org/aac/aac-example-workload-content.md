<!--Add the aac-browse-header.yml here.-->

<!--
- Add an introductory section that doesn't have a heading.
- Include 1-2 sentences to briefly explain this architecture.
- Place all scenario information in the **Scenario details** section that's located below the **Architecture** H2 heading, the **Alternatives** H3 header, and above the **Considerations** H2 heading. This includes the **Potential use cases** H3 section that goes under the **Scenario details** H2 section.
-->

## Architecture
<!--
- Visio or PowerPoint files aren't allowed in the GitHub repo. Send the file or provide a link so that the file can be uploaded to our limited-access CDN server.
- Ensure that alt text is descriptive, between 40 and 150 characters, and ends with a period.
- Update the following image syntax for the architecture diagram, and the Visio file or PowerPoint file text.
-->

![Diagram that shows the <solution name> architecture.](./images/<file-name>.png)

*Download a [Visio file](https://arch-center.azureedge.net/[file-name].vsdx) of this architecture.*

### Dataflow
<!--
- Title this section **Workflow** if data isn't in the scenario.
- Include a numbered list that describes the dataflow or workflow of each step in the solution. Start from the user or external data source, and then follow the flow through the rest of the solution. The following section uses the previous diagram as an example.
-->

The following dataflow corresponds to the previous diagram:

1. Admin 1 adds, updates, or deletes an entry in Admin 1's fork of the Microsoft 365 configuration file.
2. Admin 1 commits and syncs the changes to Admin 1's forked repository.
3. Admin 1 creates a pull request to merge the changes to the main repository.
4. The build pipeline runs on the PR.

### Components
<!-- 
- Add a bulleted list of all the components in the architecture. It includes all relevant Azure services and has links to the Azure Well-Architected Framework service guide for the product.
- Describe why each component is necessary and what it does.
- Link the name of the service via embedded link to the Well-Architected Framework service guide if it exists, or to the service's product page. Exclude the localization part of the URL, such as `en-us` unless it won't work without it.
- Update the following list of example components for your article.
-->

Examples:

- [Azure App Service](https://azure.microsoft.com/services/app-service) is a compute service that is specifically built to host web applications. In this architecture ….
- [Azure Cosmos DB for NoSQL](/azure/well-architected/service-guides/cosmos-db) is a …. In this architecture ….
- [Azure OpenAI](/azure/well-architected/service-guides/azure-openai) is a …. In this architecture ….
- [Log Analytics](/azure/well-architected/service-guides/azure-log-analytics) is a …. In this architecture ….
- [Virtual Machines](/azure/well-architected/service-guides/virtual-machines) is a …. In this architecture ….

### Alternatives
<!--
- List alternative Azure services or architectures for this solution. 
- Include reasons to choose these alternatives. Customers find this valuable because they want to know what other services or technologies that they can use as part of this architecture.
-->

## Scenario details
<!--
- This section is an explanation of the business problem and why this scenario was built to solve it. Answer the following questions:
- What prompted them to solve the problem?
- What services were used to build out this solution?
- What does this example scenario show? 
- What are the customer's goals?
- What are the benefits of implementing the solution?
-->

### Potential use cases
<!--
- Use industry keywords when possible to get the article into the proper search and filter results. These keywords are retail, finance, manufacturing, healthcare, government, energy, telecommunications, education, automotive, nonprofit, game, media (media and entertainment), travel (includes hospitality, like restaurants), facilities (includes real estate), aircraft (includes aerospace and satellites), agriculture, and sports.
- Describe any other use cases or industries where this would be a good fit.
- Explain how similar or different they are to what's in this article.
-->

## Considerations
<!--REQUIRED STATEMENT: Include the following statement to introduce this section:-->

These considerations implement the pillars of the Azure Well-Architected Framework, which is a set of guiding tenets that you can use to improve the quality of a workload. For more information, see [Well-Architected Framework](/azure/well-architected/).

<!--
- Describe any lessons learned from running this that would be helpful for new customers. 
- Describe what went wrong and what went right when building it out. 
- Describe how to manage, maintain, and monitor this long term.

REQUIREMENTS:
- Include the **Cost Optimization** section.
- Include at least two of the other H3 sub-sections. These sub-sections are Reliability, Security, Cost Optimization, Operational Excellence, and Performance Efficiency.
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

### Cost Optimization
<!--
- REQUIRED: This section is required. Cost is of the utmost importance to our customers.
- REQUIRED STATEMENT: Include the following statement to introduce the section:
-->

Cost Optimization is about looking at ways to reduce unnecessary expenses and improve operational efficiencies. For more information, see [Design review checklist for Cost Optimization](/azure/well-architected/cost-optimization/checklist).

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

### Operational Excellence
<!--REQUIRED STATEMENT: If you use this section, include the following statement:-->

Operational Excellence covers the operations processes that deploy an application and keep it running in production. For more information, see [Design review checklist for Operational Excellence](/azure/well-architected/operational-excellence/checklist).

<!--
- Include DevOps, monitoring, and diagnostics considerations in this section.
- Describe how to think about operating this solution.
-->

### Performance Efficiency
<!--REQUIRED STATEMENT: If you use this section, include the following statement:-->

Performance Efficiency refers to the ability of your workload to scale efficiently to meet user demands. For more information, see [Design review checklist for Performance Efficiency](/azure/well-architected/performance-efficiency/checklist).

<!--
- Include scalability considerations in this section.
- Answer the following questions:
  - Are there any key performance considerations beyond the typical?`
  - Are there any size considerations around this solution specifically?
  - What scale does this work at?  
  - At what point do things break or not make sense for this architecture?
-->

## Deploy this scenario
<!--
- This section is optional but greatly encouraged.
- Answer the following questions:
  - Is there an example deployment that can show me this in action?
  - What would I need to change to run this in production?
-->

## Contributors
<!--This section is expected but optional if all the contributors prefer not to include it.

1. Start with the explanation text in italics that's the same for every article. This makes it clear that Microsoft takes responsibility for the article and not a single contributor.

1. Include the list of "Principal authors" and the list of "Additional contributors," if there are any. Format in plain text, not italics or bold.

1. Link each contributor's name to the person's LinkedIn profile. 

1. Insert a pipe symbol ("|") with spaces after the name, and then enter the person's title. To minimize edits or updates, don't include the person's company, MVP status, or links to additional profiles. 
-->

*This article is maintained by Microsoft. It was originally written by the following contributors.*

Principal authors: <!--List only the primary authors. List them alphabetically and by last name. Use the *First-name Last-name* format. If the article is rewritten, keep the original authors and add the new ones. List each primary author, even if there are 10 of them. Update the following example text.-->

 - [Author 1 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"
 - [Author 2 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"

Other contributors: <!--Include the contributing authors, editors who make major content changes, and technical reviewers. List them alphabetically and by last name. Use the *First-name Last-name* format. It's okay to add newer contributors.-->

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

- [Azure Kubernetes Service (AKS) documentation](/azure/aks)
- [Azure Machine Learning documentation](/azure/machine-learning)
- [What is Azure Active Directory B2C?](/azure/active-directory-b2c/overview)
- [Application Insights overview](/azure/azure-monitor/app/app-insights-overview)

## Related resources
<!--
- Add a bulleted list of related resource links.
- Use this section for architecture information that's relevant to the current article. It must be content that the Azure Architecture Center TOC refers to but can be from a repo other than the AAC repo.
- Ensure that links to articles in the AAC repo are repo-relative, such as (../../solution-ideas/articles/article-name.yml).
- Update the following example links.
-->

Examples:

- [Artificial intelligence (AI) - Architectural overview](/azure/architecture/data-guide/big-data/ai-overview)
- [Choosing a Microsoft cognitive services technology](/azure/architecture/data-guide/technology-choices/cognitive-services)
- [Chatbot for hotel reservations](/azure/architecture/example-scenario/ai/commerce-chatbot)
- [Build an enterprise-grade conversational bot](/azure/architecture/reference-architectures/ai/conversational-bot)
- [Speech-to-text conversion](/azure/architecture/reference-architectures/ai/speech-ai-ingestion)
