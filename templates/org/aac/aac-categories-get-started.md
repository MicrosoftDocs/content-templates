
```markdown
<!-- 
Don't add metadata to this Markdown file.
The YAML file contains the metadata. 
-->

# {Category} architecture design

<!-- Add a brief introductory paragraph with no heading. -->

[2-3 sentence opening paragraph describing the category and its business value]

[Second paragraph explaining trends and why organizations adopt Azure for this category]

Whether your organization is just starting to evaluate cloud-based {category} tools or is looking to expand your current implementation, Azure provides many options. The workflow starts with learning about common approaches and aligning processes and roles around a cloud mindset.

[OPTIONAL - For multi-service categories:]
These are some of the key {category} services available on Azure:

- [Azure Service 1](/azure/{service}). Brief description.
- [Azure Service 2](/azure/{service}). Brief description.
- [Azure Service 3](/azure/{service}). Brief description.

## Architecture

<!-- This section is optional but recommended. Use the following format: -->

:::image type="complex" border="false" source="../images/{category-name}-get-started-diagram.svg" alt-text="Diagram that shows the {category} solution journey on Azure." lightbox="../images/{category-name}-get-started-diagram.svg":::
   Diagram showing the solution journey for {category} on Azure. The journey starts with learning and organizational readiness, then moves to choosing appropriate Azure services, followed by implementation best practices and production deployment.
:::image-end:::

*Download a [Visio file](https://arch-center.azureedge.net/{category-name}-get-started-diagram.vsdx) of this architecture.*

## Learn about {Category} on Azure

If you're new to {category} on Azure, the best place to learn more is with [Microsoft Learn](/training/?WT.mc_id=learnaka), a free, online training platform. You'll find videos, tutorials, and hands-on learning for specific products and services, plus learning paths based on your job role, such as developer or data analyst.

Here are some [resources|learning paths and modules] to get you started:

- [Browse Azure {category} topics](/training/browse/?products=azure&terms={search-terms})
- [Learning path: {Path name}](/training/paths/{path-id})
- [Module: {Module name}](/training/modules/{module-id})
- [Module: {Module name}](/training/modules/{module-id})

[OPTIONAL - For complex categories with multiple roles:]

### Learning paths by role

- **{Role 1}**: [{Learning path name}](/training/paths/{path-id})
- **{Role 2}**: [{Learning path name}](/training/paths/{path-id})
- **{Role 3}**: [{Learning path name}](/training/paths/{path-id})

## Organizational readiness

If your organization is new to the cloud, the [Cloud Adoption Framework](/azure/cloud-adoption-framework/) can help you get started. This collection of documentation and best practices offers proven guidance from Microsoft designed to accelerate your cloud adoption journey.

[OPTIONAL - Add 1-3 category-specific CAF links:]

Specific guidance for {category} includes:

- [{CAF topic 1}](/azure/cloud-adoption-framework/{path})
- [{CAF topic 2}](/azure/cloud-adoption-framework/{path})
- [{CAF topic 3}](/azure/cloud-adoption-framework/{path})

To help assure the quality of your {category} solution on Azure, we recommend following the [Azure Well-Architected Framework](/azure/well-architected/). It provides prescriptive guidance for organizations seeking architectural excellence and discusses how to design, provision, and monitor cost-optimized Azure solutions.

[OPTIONAL - Add category-specific WAF links:]

For {category}-specific guidance:

- [Azure Well-Architected Framework for {workload type}](/azure/well-architected/{path})
- [{Pillar} for {category} workloads](/azure/well-architected/{path})

---

## OPTION A: Implementation checklist
<!-- Use for complex infrastructure categories: Compute, Containers, Networking -->

As you're looking to implement your own {category} solution on Azure, ensure you've reviewed the following topics:

> [!div class="checklist"]
>
> - Choose the appropriate [architecture](#topic-1) based on your requirements
> - Know which [compute/service](#topic-2) options are right for your workload
> - Identify the right [storage/networking](#topic-3) solution that meets your needs
> - Decide how you're going to [manage](#topic-4) all your resources
> - Optimize your [application](#topic-5) for the cloud
> - [Secure](#topic-6) your infrastructure

### Topic 1: {Topic name}

[Detailed explanation with bullet points or subsections]

#### Subtopic

[Content with links to relevant documentation]

- [Link 1](/azure/{path})
- [Link 2](/azure/{path})

### Topic 2: {Topic name}

[Continue for each checklist item...]

---

## OPTION B: Path to production
<!-- Use for most categories: Platform services, development practices, cross-cutting -->

[1-2 sentences describing key decisions and first steps]

Key decision points include:

- **Decision area 1**: Options and trade-offs to consider
- **Decision area 2**: Factors that influence your choice
- **Decision area 3**: Implementation approaches available

To get started, consider the following example implementations:

- [{Example 1 name}](../../{path}/{article}.yml) - [Brief description of what makes this example useful]

- [{Example 2 name}](../../{path}/{article}.yml) - [Brief description of scenario]

- [{Example 3 name}](../../{path}/{article}.yml) - [Brief description of approach]

- [{Example 4 name}](../../{path}/{article}.yml) - [Brief description of use case]

- [{Example 5 name}](../../{path}/{article}.yml) - [Brief description of pattern]

---

## Best practices

[Opening sentence about importance of best practices for this category]

[APPROACH 1: General best practices list - Most common]

The [Microsoft Azure Well-Architected Framework](/azure/well-architected/) provides reference guidance and best practices. The framework comprises five pillars: Reliability, Security, Cost Optimization, Operational Excellence, and Performance Efficiency.

At the highest level, [information security](/azure/architecture/framework/security/overview) practices help ensure that your {category-specific resources} are protected. Trustworthy {category} solutions implement:

- [Governance policies](/azure/architecture/framework/security/design-governance) - [Brief category-specific guidance]

- [Identity and access management](/azure/architecture/framework/security/design-identity) - [Brief category-specific guidance]

- [Network security controls](/azure/architecture/framework/security/design-network) - [Brief category-specific guidance]

- [Data protection](/azure/architecture/framework/security/design-storage) - [Brief category-specific guidance]

At the platform level, the following best practices contribute to {category benefits} on Azure:

- **{Best practice 1}** - [Explanation with actionable guidance]

- **{Best practice 2}** - [Explanation with actionable guidance]

- **{Best practice 3}** - [Explanation with actionable guidance]

- **{Best practice 4}** - [Explanation with actionable guidance]

- **{Best practice 5}** - [Explanation with actionable guidance]

[APPROACH 2: Organized by topic/pillar - For DevOps, Management & Governance]

### {Topic 1 - e.g., Security}

- [{Best practice document 1}](/azure/{path})
- [{Best practice document 2}](/azure/{path})
- [{Best practice document 3}](/azure/{path})

### {Topic 2 - e.g., Cost Optimization}

- [{Best practice document 1}](/azure/{path})
- [{Best practice document 2}](/azure/{path})

### {Topic 3 - e.g., Operations}

- [{Best practice document 1}](/azure/{path})
- [{Best practice document 2}](/azure/{path})

[APPROACH 3: Service-specific - For Storage, Virtual Desktop, Mgmt & Governance]

Depending on the {category} technology you use, see the following best practices resources:

### {Service 1 name}

See the following guides for information about {Service 1}:

- [{Guide 1}](/azure/{path})
- [{Guide 2}](/azure/{path})
- [{Guide 3}](/azure/{path})

### {Service 2 name}

See the following guides for information about {Service 2}:

- [{Guide 1}](/azure/{path})
- [{Guide 2}](/azure/{path})

---

## OPTIONAL: Operations guide
<!-- Use for complex infrastructure with Day-2 operations: Containers, Compute, Networking -->

Getting your workload deployed on Azure is a great milestone, and this is when [day-2 operations](https://dzone.com/articles/defining-day-2-operations) become critical. **The {category} day-2 operations guide** helps ensure you're ready to meet operational demands.

> [!div class="nextstepaction"]
> [{Category} day-2 operations guide](../../operator-guides/{path}.md)

Key operational areas:

- [Monitoring and observability](../../operator-guides/{path}.md)
- [Backup and recovery procedures](../../operator-guides/{path}.md)
- [Patch and upgrade strategies](../../operator-guides/{path}.md)
- [Troubleshooting guide](../../operator-guides/{path}.md)
- [Performance optimization](../../operator-guides/{path}.md)

---

## Stay current with {Category}

[Platform/Service] is evolving rapidly. Stay informed about the latest updates and planned features:

Get the latest updates on [Azure {category} [products and features|services|technologies]](https://azure.microsoft.com/updates/?category={category-slug}).

[OPTIONAL - For categories with public roadmap:]

The platform roadmap helps you understand planned features and deprecations:

> [!div class="nextstepaction"]
> [{Category} product roadmap](https://aka.ms/{product}/roadmap)

[OPTIONAL - For specific products with detailed release notes:]

Stay current with {Product} by monitoring these resources:

- [{Product} Feature Timeline](/azure/{service}/release-notes/features-timeline)
- [{Product} documentation - What's new?](/azure/{service}/release-notes/docswhatsnew)
- [{Product} Release Notes](/azure/{service}/release-notes)

---

## Additional resources

{Category} is a broad category and covers a range of solutions. The following resources can help you discover more about Azure.

### OPTIONAL: Hybrid [and multi-cloud]
<!-- Include if category commonly used in hybrid deployments -->

The vast majority of organizations need a hybrid approach to {category} because [explain why - e.g., "their data is hosted both on-premises and in the cloud"]. Organizations often [extend on-premises {category} solutions to the cloud](../../databases/guide/hybrid-on-premises-and-cloud.md). To connect environments, organizations must [choose a hybrid network architecture](../../reference-architectures/hybrid-networking/index.yml).

Key hybrid {category} scenarios:

- **{Scenario 1}**: [{Link text}](/azure/{path}) - [Brief description]
- **{Scenario 2}**: [{Link text}](/azure/{path}) - [Brief description]
- **{Scenario 3}**: [{Link text}](/azure/{path}) - [Brief description]

### OPTIONAL: {Specialized topic 1}
<!-- E.g., "Real-time processing", "Advanced analytics", "Industry solutions" -->

[Brief introduction paragraph explaining this specialized area]

- [{Solution 1}](../../{path}/{article}.yml) - [Brief description]
- [{Solution 2}](../../{path}/{article}.yml) - [Brief description]
- [{Solution 3}](../../{path}/{article}.yml) - [Brief description]

### OPTIONAL: {Specialized topic 2}
<!-- E.g., "Data governance", "Security compliance", "Multi-region" -->

[Brief introduction paragraph]

- [{Solution 1}](../../{path}/{article}.yml) - [Brief description]
- [{Solution 2}](../../{path}/{article}.yml) - [Brief description]

### Example solutions

Here are [a few|some additional] sample implementations of {category} on Azure to consider:

- [{Solution 1 name}](../../{path}/{article}.yml) - [Brief description of scenario and value]

- [{Solution 2 name}](../../{path}/{article}.yml) - [Brief description of approach]

- [{Solution 3 name}](../../{path}/{article}.yml) - [Brief description of use case]

- [{Solution 4 name}](../../{path}/{article}.yml) - [Brief description of pattern]

- [Browse more {category} examples in the Azure Architecture Center](../../browse/index.yml?azure_categories={category-filter})

### OPTIONAL: Industry-specific solutions
<!-- Include if 5+ notable industry implementations exist -->

{Category} implementations vary by industry. Explore these industry-specific architectures:

- **{Industry 1}**: [{Solution name}](../../{path}/{article}.yml) - [Brief description]
- **{Industry 2}**: [{Solution name}](../../{path}/{article}.yml) - [Brief description]
- **{Industry 3}**: [{Solution name}](../../{path}/{article}.yml) - [Brief description]

---

## AWS or Google Cloud professionals
<!-- Include if comparison documentation exists -->

These articles can help you ramp up quickly by comparing Azure {category} options to other cloud services:

- [{Comparison topic}](../../aws-professional/{article}.md) in [Database technologies on Azure and AWS](../../aws-professional/databases.md)

- [{Comparison topic}](../../gcp-professional/services.md#{anchor}) in [Google Cloud to Azure services comparison](../../gcp-professional/services.md)

[OPTIONAL - Service-specific comparisons:]

### Service comparison

- [Service comparison: {Service type}](../../aws-professional/{article}.md)
- [Service comparison: {Service type}](../../gcp-professional/services.md)

[OPTIONAL - Migration guidance:]

### Migration guidance

If you're migrating from another cloud platform:

- [Migrate {source} to {Azure service}](/azure/{service}/migration-guides/{source})
- [Migrate {source} to {Azure service}](/azure/{service}/migration-guides/{source})

---

## Contributors

<!-- This section is expected but optional if the contributors prefer to omit it. -->

*Microsoft maintains this article. The following contributors wrote this article.*

Principal authors:

<!-- List the primary authors alphabetically by last name. Use the *FirstName LastName* format. -->

- [Author 1 Name](https://www.linkedin.com/in/ProfileURL/) | Cloud Solution Architect
- [Author 2 Name](https://www.linkedin.com/in/ProfileURL/) | Principal Cloud Architect

Other contributors:

<!-- This section is optional. List contributors and technical reviewers. -->

- [Contributor 1 Name](https://www.linkedin.com/in/ProfileURL/) | Senior Content Developer
- [Contributor 2 Name](https://www.linkedin.com/in/ProfileURL/) | Technical Reviewer

*To see nonpublic LinkedIn profiles, sign in to LinkedIn.*

---

## Next steps

<!-- Add a bulleted list of links to third-party or Microsoft topics.
Link formats: 
  - Make Learn links site relative (for example, /azure/<feature>/<article-name>).
  - Start third-party links with `https://` and omit `en-us` unless the links don't work without it.
  - Omit a trailing slash, unless that is how the final URL renders after redirects.
-->

[OPTIONAL - Use sparingly - only when there's a clear immediate action]

Ready to get started? Here are some recommended next steps:

- Complete a [Microsoft Learn module](/training/modules/{module-id}) to build foundational knowledge
- Deploy your first [{resource}](/azure/{service}/{article-name})
- Explore [{resource type}](/azure/{service}/{article-name})
- Join the [{Community name}](https://techcommunity.microsoft.com/{path}) to connect with experts

---

## Related resources

<!-- Add a bulleted list of links to related architecture information in the AAC TOC. -->

- [{Related architecture 1}](../../{path}/{article}.yml)
- [{Related architecture 2}](../../{path}/{article}.yml)
- [{Product 1} documentation](/azure/{service})
- [{Product 2} documentation](/azure/{service})
- [Browse more {category} architectures](../../browse/index.yml?azure_categories={category-filter})
```