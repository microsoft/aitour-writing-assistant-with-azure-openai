# Presenter Script  

## WRK551: Build a multi-tasking assistant with Azure OpenAI   

Slide: Meet the Instructors (2 mins)  

"Welcome everyone to workshop 551, Building a multi-tasking assistant with Azure OpenAI! Before we dive into today’s session, I’d like to introduce you to our team.  

I’m [Instructor Name], and I’ll be guiding you through the main content today. Alongside me, we have our proctors: [Proctor Name], [Proctor Name], and [Proctor Name]. They are here to assist you with any questions or technical issues you might encounter. To connect to the Wi-Fi please use the Wi-Fi password on the screen.   

Feel free to reach out to any of us during the session. Now, let’s get started!"  

  

Slide: Context - Traditional LLM Applications (1 min)  

"LLMs are powerful tools for generating knowledge and are pre-trained on vast amounts of public data. Common use cases include:  

Question and Answering  

Text Generation  

Summarization  

These applications showcase the versatility and potential of LLMs in various domains."  

  

Slide: Context - Making LLM Apps Real and Useful (1 min)  

"Since the technology is so new and evolving it can be hard to build LLM applications. To make LLM applications practical for organizations, we need to address several challenges:  

Handling various real-world inputs.  

Employing evaluation techniques and prompt engineering.  

Debugging and understanding failures.  

Setting up and managing production infrastructure.  

We’ll cover these aspects to ensure your LLM applications are robust and effective."  

  

Slide: Introducing Contoso Creative (2 min)  

"In this workshop we’ll be working on a project called Contoso Creative, a multi-tasking assistant designed to help write articles that market products from an online retailer, Contoso Outdoors.  

The assistant will perform three main tasks:  

Research trending outdoorsy topics online.  

Find relevant products to include in the article.  

Edit and improve the article to make it ready for publication.  

This project will give you hands-on experience with integrating LLMs into a real-world application."  

  

Slide: Demo (Transition) (10mins)   

“Now, let us see Contoso Creative in action. I’ll share my screen and walk you through a live demo of how the assistant works and we’ll also walk through the instructions in the Skillable lab manual together so you can set things up for the workshop.”  

** When you get to this slide please do the following:  

 1. Share DEMO 1 on your screen (the demo has sound for the walk through). It is 2mins long.  

2. Share your screen and walk through the Skillable Lab Manual instructions. This process is demonstrated in DEMO 2. If you would prefer you can play DEMO 2 instead of walking through things yourself, however walking through the steps live is better. Completing this set up step should not take more than 8mins.   

 

Continue with slides once step 2 is complete.   

  

Slide: How does the assistant work? (Transition)  

 " Now that we have things set up let’s dive into a brief overview of how our assistant works." 

Slide: Contoso Creative Writer is an Agentic Application (1 mins) 

"Contoso Creative is an agentic application, meaning it can perceive its environment, make decisions, and take actions to achieve goals. 

 

Slide: Agentic Applications have LLM based control flow (2 mins) 

"Agentic applications can also be described as having LLM based control flow. This is when for example, an LLM can interact with user input, like an instruction from a user to find references to other papers in a user provided paper. The LLM can then make decisions based on this input about which function to call at what point in the flow, and execute the function, return the result to the next relevant function and continue this until it can return the completed result to the user. " 

 

Slide: Contoso Creative: Multi-agent creative writing copilot (2 minutes) 

"Contoso Creative Writer leverages several Azure services. Here’s a quick overview of how it works: 

User Input: The process begins with user input. 

Azure Managed Identity: Ensures secure access to Azure resources. 

Azure Monitor: Monitors the performance and health of the application. 

Azure Application Container (ACA): Hosts our processing services. 

Azure AI Studio: Provides the environment for developing and managing AI models. 

The assistant comprises 4 main agents: 

Researcher Agent 

Product Agent 

Writer Agent 

Editor Agent 

These agents collaborate to produce high-quality articles that market relevant products from Contoso Outdoors." 

 

Slide: Workshop Goals (Transition) 

 

Slide: Workshop Goals (2 minutes) 

"Now, let’s discuss the goals of this workshop. By the end of this session, you will be able to: 

Implement a real-world LLM lifecycle. 

Understand agents and prompt engineering with Prompty. 

Utilize tracing for debugging and observability. 

Build and run Contoso Creative. 

Set up automated evaluations with GitHub Actions. 

These goals are designed to provide you with a comprehensive understanding of building and managing a multi-agent AI application. You should all be on the WORKSHOP-README.md page and should be able to jump straight to Part 1 and continue the rest of the workshop on your own. Our team will be here to help if you get stuck and I’ll come back and share some resources when it’s time to wrap up. Have fun!" 