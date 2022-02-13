> The H1 title is a noun phrase that describes the scenario. Don't enter it here, but as the **name** value in the corresponding YML file.> 
> Include the solution idea header note at the top of the solution idea. This adds clarification why this is a scaled-back architecture (and provides consistency with our other SIs)...

[!INCLUDE [header_file](../../../includes/sol-idea-header.md)]

> Introductory section (no heading)
> The introduction contains:

- A paragraph that describes what the solution does (the domain)
- A paragraph that contains a brief description of the main Azure services that make up the solution. This paragraph should convey the Azure value proposition, not a complete description of the architecture.

## Potential use cases

> Are there any other use cases or industries where this would be a fit?
> How similar or different are they to what's in this article?

These other uses cases have similar design patterns:

- List of example use cases

## Architecture

_Architecture diagram goes here_

> Under the architecture diagram, include this sentence and a link to the Visio file or the PowerPoint file: 

_Download a [Visio file](https://arch-center.azureedge.net/[filename].vsdx) of this architecture._

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

Example: 
* [Resource Groups][resource-groups] is a logical container for Azure resources.  We use resource groups to organize everything related to this project in the Azure console.

## Next steps

> Links to articles on Docs and Learn. Could also be to appropriate sources outside of Docs, such as third-party documentation, GitHub repos, or an official technical blog post.

Examples:
* [Azure Kubernetes Service (AKS) documentation](/azure/aks)
* [Azure Machine Learning documentation](/azure/machine-learning)
* [What are Azure Cognitive Services?](/azure/cognitive-services/what-are-cognitive-services)

## Related resources

> Use "Related resources" for related architecture guides and architectures (content on the Azure Architecture Center).

> Here are example sections:

Related architecture guides:

* [Artificial intelligence (AI) - Architectural overview](/azure/architecture/data-guide/big-data/ai-overview)
* [Choosing a Microsoft cognitive services technology](/azure/architecture/data-guide/technology-choices/cognitive-services)

Fully deployable architectures:

* [Chatbot for hotel reservations](/azure/architecture/example-scenario/ai/commerce-chatbot)
* [Build an enterprise-grade conversational bot](/azure/architecture/reference-architectures/ai/conversational-bot)
* [Speech-to-text conversion](/azure/architecture/reference-architectures/ai/speech-ai-ingestion)