To help prepare content for AI Tour, please use this template repository for organizing your sessions and preparing the content for future presentors.
1. Update this readme with the todo's listed below
2. The src folder has been created for all development tasks when creating this session
3. The Lab folder is in-person and async participation with content, please update this folder with instructions for participants to follow along.
4. The Presenter Notes folder is the train the trainer section. Here add any slide decks, demo videos, and other content as needed. This page has a rough layout to provide ideas but can be edited as needed.
5. If you are taking advantage of the static front end site, edit the content in the _config.yml file as needed (specifically the title and description)


# Build a multi-tasking asssistant with Azure OpenAI

This repo is a companion to this workshop at Microsoft AI Tour, a worldwide tour of events.

> Learn more about Microsoft AI Tour on the official website.

![Session cover image with a bright "AI" text in 3D over a blue and purple abstract background.](img/session-cover.png)

## Session Desciption

In this workshop attendees will be introduced to the concept of Agents, an approach in AI that combines thought and action using LLMs and tools to achieve a desired goal. The sample presented will demonstrates how to create a Python app that takes a topic and instruction from a user then calls a research agent that uses the Bing Search API to research the topic, a product agent that uses Azure AI Search to do a semantic similarity search for related products from a vector store, a writer agent to combine the research and product information into a helpful article, and an editor agent to refine the article that's finally presented to the user. 

## Learning Outcomes

Implement a real world LLM-basedd agent lifecycle
- Understand agents and prompt engineering with [Prompty](https://prompty.ai)
- Utilize tracing for debugging and observability
- Build and run Contoso Creative Writer
- Set up automated evaluations with GitHub Actions

## Technology Used
- Backend application
  - Prompty
  - FastAPI
  - OpenTelemetry
- Frontend application
  - React
  - Typescript
  - ViteJS
- AI Models
  - GPT-4o
  - GPT-3.5 Turbo
- Tools
  - Azure AI Search
  - Bing Search
- Monitoring
  - AppInsights
  - Promptflow tracing
- Infra
  - Azure Container Applications (ACA)
  - Azure AI Hub
  - Managed identity
  - Key vault
- Infra as code
  - azd (Azure Developer CLI)
- CI/CD
  - Github Actions

## Additional Resources and Continued Learning
You can find additional resources, including the slides of the presentation, [here](./SESSION_RESOURCES.md).

If you will present this talk, you can find the [trainer resources here](./train-the-trainer/README.md). 

| Resources          | Links                             | Description        |
|:-------------------|:----------------------------------|:-------------------|
| Future Learning 1  | [Link 1](https://www.google.com/) | Learn more about X |
| Future Learning 2  | [Link 2](https://www.google.com/) | Learn more about Y |

## Content Owners


<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<table>
<tr>
    <td align="center"><a href="http://learnanalytics.microsoft.com">
        <img src="https://github.com/marlenezw.png" width="100px;" alt="Marlene Mhangami"/><br />
        <sub><b>Marlene Mhangami
</b></sub></a><br />
            <a href="https://github.com/marlenezq" title="talk">📢</a> 
    </td>
    <td align="center"><a href="http://learnanalytics.microsoft.com">
        <img src="https://github.com/cassiebreviu.png" width="100px;" alt="Cassie Breviu"/><br />
        <sub><b>Cassie Breviu
</b></sub></a><br />
            <a href="https://github.com/Cassie Breviu" title="talk">📢</a> 
    </td>
</tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Responsible AI 

Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at [https://aka.ms/RAI](https://aka.ms/RAI).
Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this sample - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the [Azure OpenAI service Transparency note](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) to be informed about risks and limitations.

The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. We also have an interactive Content Safety Studio that allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following [quickstart documentation](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using [generation quality and risk and safety metrics](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in).

You can evaluate your AI application in your development environment using the [prompt flow SDK](https://microsoft.github.io/promptflow/index.html). Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the prompt flow sdk to evaluate your system, you can follow the [quickstart guide](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk). Once you execute an evaluation run, you can [visualize the results in Azure AI Studio](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results).

