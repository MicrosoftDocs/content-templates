<!-- 
- Don't add metadata to this Markdown file. Use the browser header template to create a YAML file that contains your metadata. 
- Before the "Architecture" heading, add a brief introductory paragraph with no heading. 
-->

## Architecture

<!-- Architecture diagram goes here. Use the following format:-->

:::image type="content" border="false" source="./images/<file-name>.png" alt-text="Diagram that shows the <solution name> architecture." lightbox="./images/<file-name>.png":::

<!-- In the following line, the link will work after the AAC team uploads your Visio or PowerPoint file to the Azure CDN. -->

*Download a [Visio file](https://arch-center.azureedge.net/<file-name>.vsdx) of this architecture.*

### Dataflow
<!--
- If your scenario doesn't include data, title this section "Workflow".
- Add a numbered list for the steps in your dataflow or workflow.
-->

The following dataflow corresponds to the previous diagram:

<!-- Example list:
1. Admin 1 adds, updates, or deletes an entry in Admin 1's fork of the Microsoft 365 configuration file.
2. Admin 1 commits and syncs the changes to Admin 1's forked repository.
3. Admin 1 creates a pull request to merge the changes to the main repository.
4. The build pipeline runs on the PR.
-->

### Components
<!-- 
- Add a bulleted list of all components in the architecture. 
- Where possible, link to the component's Well-Architected Framework service guide. Alternatively, link to the product page.

Example list: 
- [Azure App Service](https://azure.microsoft.com/services/app-service) is a compute service that is specifically built to host web applications. In this architecture ….
- [Azure Cosmos DB for NoSQL](/azure/well-architected/service-guides/cosmos-db) is a …. In this architecture ….
- [Azure OpenAI](/azure/well-architected/service-guides/azure-openai) is a …. In this architecture ….
- [Log Analytics](/azure/well-architected/service-guides/azure-log-analytics) is a …. In this architecture ….
- [Azure Virtual Machines](/azure/well-architected/service-guides/virtual-machines) is a …. In this architecture ….

-->

### Alternatives
<!-- 
- List alternative Azure services or architectures for this solution. 
- Include reasons to choose these alternatives.
-->

## Scenario details
<!-- Explain the business problem and why this scenario was built to solve it. 

Questions this section can address:
- What services were used to build out this solution?
- What does this example scenario show? 
- What are the customer's goals?
- What are the benefits of implementing the solution?
-->

### Potential use cases
<!--
- List example use cases.
- For SEO, use industry keywords when possible. Examples: 
  - retail 
  - finance
  - manufacturing
  - healthcare
  - government
  - energy
  - telecommunications
  - education
  - automotive
  - nonprofit
  - game
  - media (media and entertainment) 
  - travel (includes hospitality, like restaurants)
  - facilities (includes real estate)
  - aircraft (includes aerospace and satellites)
  - agriculture
  - sports
- Explain how similar or different these use cases are to the main scenario.
-->

## Considerations
<!--REQUIRED STATEMENT: Include the following statement to introduce this section:-->

These considerations implement the pillars of the Azure Well-Architected Framework, which is a set of guiding tenets that you can use to improve the quality of a workload. For more information, see [Well-Architected Framework](/azure/well-architected/).

<!--
- Describe any lessons learned from running this that would be helpful for new customers. 
- Describe what went wrong and what went right when building it out. 
- Describe how to manage, maintain, and monitor it long term.

REQUIREMENTS:
- Include the **Cost Optimization** H3 section.
- Include at least two of the other H3 sub-sections, in the order shown below. 
-->

### Reliability
<!--REQUIRED STATEMENT: If you use this section, include the following statement:-->

Reliability ensures that your application can meet the commitments you make to your customers. For more information, see [Design review checklist for Reliability](/azure/well-architected/reliability/checklist).

<!--
- Include resiliency and availability considerations. These considerations can be H4 headers.
- Describe any key resilience and reliability considerations that aren't typical.
-->

### Security
<!--REQUIRED STATEMENT: If you use this section, include the following statement:-->

Security provides assurances against deliberate attacks and the abuse of your valuable data and systems. For more information, see [Design review checklist for Security](/azure/well-architected/security/checklist).

<!--
> Include identity and data sovereignty considerations.
> Explain any security considerations (beyond the typical).
> Include your Azure security baseline assessment recommendations.
-->

### Cost Optimization

<!-- REQUIRED: This section and the following statement are required. -->

Cost Optimization is about looking at ways to reduce unnecessary expenses and improve operational efficiencies. For more information, see [Design review checklist for Cost Optimization](/azure/well-architected/cost-optimization/checklist).

<!-- Address questions such as these:
- How much will this cost to run? (Don't give dollar amounts.)
- Are there ways to save costs?
- If it scales linearly, break it down by cost/unit. If it doesn't, why?
- What components make up the cost?
- How does scale affect the cost?

Link to the pricing calculator (https://azure.microsoft.com/pricing/calculator). Include the major cost-driving components, a typical scale or throughput, and recommended SKUs. -->

### Operational Excellence

<!--REQUIRED STATEMENT: If you use this section, include the following statement:-->

Operational Excellence covers the operations processes that deploy an application and keep it running in production. For more information, see [Design review checklist for Operational Excellence](/azure/well-architected/operational-excellence/checklist).

<!--
How do customers need to think about operating this solution? 
Consider DevOps, monitoring, and diagnostics. 
-->


### Performance Efficiency

<!--REQUIRED STATEMENT: If you use this section, include the following statement:-->

Performance Efficiency is the ability of your workload to scale to meet the demands placed on it by users in an efficient manner. For more information, see [Design review checklist for Performance Efficiency](/azure/well-architected/performance-efficiency/checklist).

<!--
Explain key performance considerations, beyond the typical.
-->

## Contributors
<!-- This section is expected but optional if the contributors prefer to omit it. Implement this format: -->

*This article is maintained by Microsoft. It was originally written by the following contributors.*

Principal authors: 

<!--List the primary authors alphabetically and by last name. Use the *FirstName LastName* format.-->

- [Author 1 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"
- [Author 2 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"

Other contributors: 

<!--This section is optional. List contributors and technical reviewers. -->

- [Contributor 1 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"
- [Contributor 2 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"

*To see non-public LinkedIn profiles, sign in to LinkedIn.*

## Next steps
<!--
- Add a bulleted list of links to third-party or Microsoft topics that can help customers build the workload.
- Link formats: 
  - Make Learn links site relative (for example, /azure/<feature>/<article-name>).
  - Start third-party links with `https://` and omit `en-us` unless the links don't work without it.
  - Omit a trailing slash.

Example list:

- [Azure Kubernetes Service (AKS) documentation](/azure/aks)
- [Azure Machine Learning documentation](/azure/machine-learning)
- [What is Azure Active Directory B2C?](/azure/active-directory-b2c/overview)
- [Application Insights overview](/azure/azure-monitor/app/app-insights-overview)
-->

## Related resources
<!-- Add a bulleted list of links to related architecture information in the AAC TOC.

Example list:

- [Artificial intelligence (AI) - Architectural overview](/azure/architecture/data-guide/big-data/ai-overview)
- [Choosing a Microsoft cognitive services technology](/azure/architecture/data-guide/technology-choices/cognitive-services)
- [Chatbot for hotel reservations](/azure/architecture/example-scenario/ai/commerce-chatbot)
- [Build an enterprise-grade conversational bot](/azure/architecture/reference-architectures/ai/conversational-bot)
- [Speech-to-text conversion](/azure/architecture/reference-architectures/ai/speech-ai-ingestion)
-->
