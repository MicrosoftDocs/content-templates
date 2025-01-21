<!-- 
- Don't add metadata to this Markdown file. Use the browser header template to create a YAML file that contains your metadata. 
- Before the "Architecture" heading, add a brief introduction of no more than three sentences. Format it as a single paragraph with no heading. 
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
- Explain how similar or different these use cases are to the main scenario.
-->

## Contributors

<!-- 
- This section is expected but optional if the contributors prefer to omit it. 
- Implement this format: 
-->

*This article is maintained by Microsoft. It was originally written by the following contributors.*

Principal authors: 

<!--
- List the primary authors alphabetically and by last name. 
- Use the *FirstName LastName* format.
-->

- [Author 1 Name](https://linkedin.com/in/ProfileURL) | Title, such as "Cloud Solution Architect"
- [Author 2 Name](https://linkedin.com/in/ProfileURL) | Title, such as "Cloud Solution Architect"

Other contributors: 

<!--
- This section is optional. 
- List contributors and technical reviewers. 
-->

- [Contributor 1 Name](https://linkedin.com/in/ProfileURL) | Title, such as "Cloud Solution Architect"
- [Contributor 2 Name](https://linkedin.com/in/ProfileURL) | Title, such as "Cloud Solution Architect"

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

Example lists:

Related architecture guides:

- [Artificial intelligence (AI) architecture design](/azure/architecture/ai-ml)
- [Choose a Microsoft AI services technology](/azure/architecture/data-guide/technology-choices/ai-services)

Fully deployable architectures:

- [Image classification on Azure](../../example-scenario/ai/intelligent-apps-image-processing.yml)
- [Baseline OpenAI end-to-end chat reference architecture](./ai-ml/architecture/baseline-openai-e2e-chat.yml)
- [Azure OpenAI chat baseline architecture in an Azure landing zone](./ai-ml/architecture/azure-openai-baseline-landing-zone.yml)
- [Extract and analyze call center data](./ai-ml/architecture/openai/architecture/call-center-openai-analytics.yml)
-->