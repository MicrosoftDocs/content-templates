<!-- 
- Don't add metadata to this Markdown file. Use the browser header template to create a YAML file that contains your metadata. 
- Before the "Architecture" heading, add a brief introductory paragraph with no heading. 
-->

## Architecture

<!-- Architecture diagram goes here. Use the following format to link to your image file:-->

:::image type="content" border="false" source="./images/<file-name>.png" alt-text="Diagram that shows the <solution name> architecture." lightbox="./images/<file-name>.png":::

<!-- Under the architecture diagram, link to the Visio or PowerPoint file. The link will work after the AAC team uploads your Visio or PowerPoint file to the Azure CDN. -->

*Download a [Visio file](https://arch-center.azureedge.net/<file-name>.vsdx) of this architecture.*

### Dataflow

<!--
- If your scenario doesn't include data, title this section "Workflow".
- Add a numbered list for the steps in your architecture diagram.
-->

### Components
<!-- 
- Add a bulleted list of all components in the architecture. 
- Where possible, link to the component's Well-Architected Framework service guide. Alternatively, link to the product page.

Example list:

- [Machine Learning](/azure/well-architected/service-guides/azure-machine-learning) is a managed cloud service that you can use to train, deploy, and manage machine learning models. This architecture uses several other features of Machine Learning that are used to develop and deploy executable flows for AI applications that are powered by language models.
- [Container Registry](/azure/container-registry/) lets you build, store, and manage container images and artifacts in a private registry for all types of container deployments. In this architecture, flows are packaged as container images and stored in Container Registry.
- [Azure AI Search](/azure/search/) is a cloud search service that supports [full-text search](/azure/search/search-lucene-query-architecture), [semantic search](/azure/search/semantic-search-overview), [vector search](/azure/search/vector-search-overview), and [hybrid search](/azure/search/vector-search-ranking#hybrid-search). AI Search is included in the architecture because it's a common service used in the flows behind chat applications. AI Search can be used to retrieve and index data that's relevant for user queries. The prompt flow implements the RAG [Retrieval Augmented Generation](/azure/search/retrieval-augmented-generation-overview) pattern to extract the appropriate query from the prompt, query AI Search, and use the results as grounding data for the Azure OpenAI model.
-->

### Alternatives
<!-- 
- List alternative Azure services or architectures for this solution. 
- Include reasons to choose these alternatives.
-->

## Scenario details
<!--
- Explain the business problem and why this scenario was built to solve it.
- Answer the questions like these:
  - What prompted the problem?
  - What services were used in building out this solution?
  - What does this example scenario show? 
  - What are the customer's goals?
  - What are the benefits of implementing the solution?
-->

### Potential use cases
<!--
- Describe any other use cases or industries where this would be a fit.
- Describe how similar or different they are to what's in the article.
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
-->

These other uses cases have similar design patterns:
<!--List example use cases.-->

## Recommendations

You can apply the following recommendations to most scenarios. Follow these recommendations unless you have a specific requirement that overrides them.

<!--Include considerations for how to deploy or configure the elements of this architecture.-->

## Considerations

<!--REQUIRED STATEMENT: Include the following statement to introduce this section:-->

These considerations implement the pillars of the Azure Well-Architected Framework, which is a set of guiding tenets that you can use to improve the quality of a workload. For more information, see [Microsoft Azure Well-Architected Framework](/azure/well-architected/).

<!--
In this section, you can answer questions such as these:
- What lessons did we learn that would be helpful for new customers?  
- What went wrong or right when building it out?
- How do I need to consider to manage, maintain, and monitor this long term?

Include ALL of the following H3 sub-sections, in the following order.
-->

### Reliability

<!--REQUIRED STATEMENT: Include the following statement to introduce the section:-->

Reliability ensures your application can meet the commitments you make to your customers. For more information, see [Design review checklist for Reliability](/azure/well-architected/reliability/checklist).

<!--
- Include resiliency and availability considerations. These considerations can be H4 headers.
- Describe any key resilience and reliability considerations that aren't typical.
-->

### Security

<!--REQUIRED STATEMENT: Include the following statement to introduce the section:-->

Security provides assurances against deliberate attacks and the abuse of your valuable data and systems. For more information, see [Design review checklist for Security](/azure/well-architected/security/checklist).

<!--
> Include identity and data sovereignty considerations.
> Explain any security considerations (beyond the typical).
> Include your Azure security baseline assessment recommendations.
-->

### Cost Optimization

<!--REQUIRED STATEMENT: Include the following statement to introduce the section:-->

Cost Optimization is about looking at ways to reduce unnecessary expenses and improve operational efficiencies. For more information, see [Design review checklist for Cost Optimization](/azure/well-architected/cost-optimization/checklist).

<!-- Address questions such as these:
- How much will this cost to run? (Don't give dollar amounts.)
- Are there ways to save costs?
- If it scales linearly, break it down by cost/unit. If it doesn't, why?
- What components make up the cost?
- How does scale affect the cost?

Link to the pricing calculator (https://azure.microsoft.com/pricing/calculator). Include the major cost-driving components, a typical scale or throughput, and recommended SKUs. -->

### Operational Excellence

<!--REQUIRED STATEMENT: Include the following statement to introduce the section:-->

Operational Excellence covers the operations processes that deploy an application and keep it running in production. For more information, see [Design review checklist for Operational Excellence](/azure/well-architected/operational-excellence/checklist).

<!--
How do customers need to think about operating this solution? 
Consider DevOps, monitoring, and diagnostics. 
-->

### Performance Efficiency

<!--REQUIRED STATEMENT: Include the following statement to introduce the section:-->

Performance Efficiency is the ability of your workload to scale to meet the demands placed on it by users in an efficient manner. For more information, see [Design review checklist for Performance Efficiency](/azure/well-architected/performance-efficiency/checklist).

<!-- 
- Explain key performance considerations, beyond the typical. 
- This includes scalability considerations.
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

- [Azure Machine Learning documentation](/azure/machine-learning)
- [What are Azure AI Services?](/azure/ai-services/what-are-ai-services)
-->

## Related resources

<!-- Add a bulleted list of links to related architecture information in the AAC TOC.

Example list:

- [Baseline Azure OpenAI reference architecture](/azure/architecture/ai-ml/architecture/baseline-openai-e2e-chat)
- [Build an enterprise-grade conversational bot](/azure/architecture/reference-architectures/ai/conversational-bot)
- [Speech-to-text conversion](/azure/architecture/reference-architectures/ai/speech-ai-ingestion)
-->
