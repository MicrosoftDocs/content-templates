<!-- Use the aac-browse-header.yml -->

> The H1 title is a noun phrase with a present tense verb that describes the scenario (no gerunds, "-ing" verbs). Don't enter it here, but as the **name** value in the corresponding YML file.> 
> Include the solution idea header note at the top of the solution idea. This adds clarification why this is a scaled-back architecture (and provides consistency with our other SIs)...

[!INCLUDE [header_file](../../../includes/sol-idea-header.md)]

> Introductory section - no heading
>> In this section, include 1-2 sentences to briefly explain this architecture. 
>> The full scenario info will go in the "Scenario details" section, which is below the "Architecture" H2 (top level) heading, below the "Components" H3 header, and above the "Contributors" H2 (top level) header. That includes the "Potential use cases" H3 section, which goes under the "Scenario details" H2 section. The reason why we moved this content down lower, is because customers want the emphasis on the diagram and architecture first, not the scenario.

## Architecture

> Architecture diagram goes here. Use the following format:

![Diagram of the <solution name> architecture.](./images/<file-name>.png)

> Under the architecture diagram, include this sentence and a link to the Visio file or the PowerPoint file: 

*Download a [Visio file](https://arch-center.azureedge.net/[file-name].vsdx) of this architecture.*

> Note that Visio or PowerPoint files are not allowed in the GitHub repo. Send the file or provide a link so the file can be uploaded to our limited-access CDN server.

### Dataflow

> An alternate title for this sub-section is "Workflow" (if data isn't really involved).
> In this section, include a numbered list that annotates/describes the dataflow or workflow through the solution. Explain what each step does. Start from the user or external data source, and then follow the flow through the rest of the solution (as shown in the diagram).

Examples:
1. Admin 1 adds, updates, or deletes an entry in Admin 1's fork of the Microsoft 365 config file.
2. Admin 1 commits and syncs the changes to Admin 1's forked repository.
3. Admin 1 creates a pull request (PR) to merge the changes to the main repository.
4. The build pipeline runs on the PR.

### Components

> A bullet list of components in the architecture (including all relevant Azure services) with links to the product service pages. This is for lead generation (what business, marketing, and PG want). It helps drive revenue.

> Why is each component there?
> What does it do and why was it necessary?
> Link the name of the service (via embedded link) to the service's product service page. Be sure to exclude the localization part of the URL (such as "en-US/").

Example: 
* [Resource Groups][resource-groups] is a logical container for Azure resources.  We use resource groups to organize everything related to this project in the Azure console.

## Scenario details

> This should be an explanation of the business problem and why this scenario was built to solve it.
>> What prompted them to solve the problem?
>> What services were used in building out this solution?
>> What does this example scenario show? What are the customer's goals?

> What were the benefits of implementing the solution?

### Potential use cases

> What industry is the customer in? Use the following industry keywords, when possible, to get the article into the proper search and filter results: retail, finance, manufacturing, healthcare, government, energy, telecommunications, education, automotive, nonprofit, game, media (media and entertainment), travel (includes hospitality, like restaurants), facilities (includes real estate), aircraft (includes aerospace and satellites), agriculture, and sports. 
>> Are there any other use cases or industries where this would be a fit?
>> How similar or different are they to what's in this article?

## Contributors

> (Expected, but this section is optional if all the contributors would prefer to not include it)

> Start with the explanation text (same for every section), in italics. This makes it clear that Microsoft takes responsibility for the article (not the one contributor). Then include the "Pricipal authors" list and the "Other contributors" list, if there are additional contributors (all in plain text, not italics or bold). Link each contributor's name to the person's LinkedIn profile. After the name, place a pipe symbol ("|") with spaces, and then enter the person's title. We don't include the person's company, MVP status, or links to additional profiles (to minimize edits/updates). Implement this format:

*This article is maintained by Microsoft. It was originally written by the following contributors.*

Principal authors: > Only the primary authors. Listed alphabetically by last name. Use this format: Fname Lname. If the article gets rewritten, keep the original authors and add in the new one(s).

 - [Author 1 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"
 - [Author 2 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"
 - > Continue for each primary author (even if there are 10 of them).

Other contributors: > (If applicable.) Include contributing (but not primary) authors, major editors (not minor edits), and technical reviewers. Listed alphabetically by last name. Use this format: Fname Lname. It's okay to add in newer contributors.

 - [Contributor 1 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"
 - [Contributor 2 Name](http://linkedin.com/ProfileURL) | Title, such as "Cloud Solution Architect"
 - > Continue for each additional contributor (even if there are 10 of them).

*To see non-public LinkedIn profiles, sign in to LinkedIn.*

## Next steps

> Links to articles on Microsoft Learn. Could also be to appropriate sources outside of Learn, such as third-party documentation, GitHub repos, or an official technical blog post.

Examples:
* [Azure Kubernetes Service (AKS) documentation](/azure/aks)
* [Azure Machine Learning documentation](/azure/machine-learning)
* [What are Azure Cognitive Services?](/azure/cognitive-services/what-are-cognitive-services)

## Related resources

> Use "Related resources" for architecture information that's relevant to the current article. It must be content that the Azure Architecture Center TOC refers to, but may be from a repo other than the AAC repo.
> Links to articles in the AAC repo should be repo-relative, for example (../../solution-ideas/articles/article-name.yml).

> Here are example sections:

Related architecture guides:

* [Artificial intelligence (AI) - Architectural overview](/azure/architecture/data-guide/big-data/ai-overview)
* [Choosing a Microsoft cognitive services technology](/azure/architecture/data-guide/technology-choices/cognitive-services)

Fully deployable architectures:

* [Chatbot for hotel reservations](/azure/architecture/example-scenario/ai/commerce-chatbot)
* [Build an enterprise-grade conversational bot](/azure/architecture/reference-architectures/ai/conversational-bot)
* [Speech-to-text conversion](/azure/architecture/reference-architectures/ai/speech-ai-ingestion)