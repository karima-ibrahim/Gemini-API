# Welcome to the Kaggle 5-day Generative AI course!
![Gimini](https://github.com/user-attachments/assets/b42ba9a2-9206-40d2-a519-3054f5111f0c)



## Day 1 Assignments: Foundational Large Language Models & Text Generation.

### Authors: Mohammadamin Barektain, Anant Nawalgaria, Daniel J. Mankowitz, Majd Al Merey, Yaniv Leviathan, Massimo Mascaro, Matan Kalman, Elena Buchatskaya, Aliaksei Severyn, and Antonio Gulli
### Introduction
The advent of Large Language Models (LLMs) represents a seismic shift in the world of artificial intelligence. Their ability to process, generate, and understand user intent is fundamentally changing the way we interact with information and technology.
An LLM is an advanced artificial intelligence system that specializes in processing, understanding, and generating human-like text. These systems are typically implemented as a deep neural network and are trained on massive amounts of text data. This allows them to learn the intricate patterns of language, giving them the ability to perform a variety of tasks, like machine translation, creative text generation, question answering, text summarization, and many more reasoning and language oriented tasks. This whitepaper dives into the timeline of the various architectures and approaches building up to the large language models and the architectures being used at the time of publication. It also discusses fine- tuning techniques to customize an LLM to a certain domain or task, methods to make the training more efficient, as well as methods to accelerate inference. These are then followed by various applications and code examples.

### Complete the Intro Unit - “Foundational Large Language Models & Text Generation”, which is:

- ➡️ [Optional] Listen to the summary podcast episode (https://youtu.be/mQDlCZZsOyo) for this unit (created by NotebookLM, https://notebooklm.google.com/).
- ➡️ Read the “Foundational Large Language Models & Text Generation” whitepaper (https://www.kaggle.com/whitepaper-foundational-llm-and-text-generation).

### Complete Unit 1 - “Prompt Engineering”, which is:

- ➡️ [Optional] Listen to the summary podcast episode (https://youtu.be/F_hJ2Ey4BNc) for this unit (created by NotebookLM).
- ➡️ Read the “Prompt Engineering” whitepaper (https://www.kaggle.com/whitepaper-prompt-engineering).
- Introduction
    When thinking about a large language model input and output, a text prompt (sometimes accompanied by other modalities such as image prompts) is the input the model uses to predict a specific output. You don’t need to be a data scientist or a machine learning engineer – everyone can
    write a prompt. However, crafting the most effective prompt can be complicated. Many aspects of your prompt affect its efficacy: the model you use, the model’s training data, the model configurations, your word-choice, style and tone, structure, and context all matter. Therefore,
    prompt engineering is an iterative process. Inadequate prompts can lead to ambiguous, inaccurate responses, and can hinder the model’s ability to provide meaningful output. You don’t need to be a data scientist or a machine learning engineer – everyone can write a prompt.
    When you chat with the Gemini chatbot, you basically write prompts, however this whitepaper focuses on writing prompts for the Gemini model within Vertex AI or by using the API, because by prompting the model directly you will have access to the configuration such as temperature etc.
    This whitepaper discusses prompt engineering in detail. We will look into the various prompting techniques to help you getting started and share tips and best practices to become a prompting expert. We will also discuss some of the challenges you can face while crafting prompts.
- ➡️ Complete this code lab (https://www.kaggle.com/code/markishere/day-1-prompting) on Kaggle where you’ll learn prompting fundamentals. Make sure you phone verify (https://www.kaggle.com/settings) your account before starting, it's necessary for the code labs.

## 💡 What You’ll Learn
Today you’ll explore the evolution of LLMs, from transformers to techniques like fine-tuning and inference acceleration. You’ll also get trained in the art of prompt engineering for optimal LLM interaction.

The code lab will walk you through getting started with the Gemini API and cover several prompt techniques and how different parameters impact the prompts.

## playlist of all livestreams:
 https://www.youtube.com/playlist?list=PLqFaTIg4myu-b1PlxitQdY0UYIbys-2es

# 
## Day 2 Assignments: Embeddings & Vector Stores.

### Authors: Anant Nawalgaria and Xiaoqi Ren
### Introduction
Modern machine learning thrives on diverse data—images, text, audio, and more. This whitepaper explores the power of embeddings, which transform this heterogeneous data into a unified vector representation for seamless use in various applications. We'll guide you through:
 Understanding Embeddings: Why they are essential for handling multimodal data and their diverse applications.
 Embedding Techniques: Methods for mapping different data types into a common vector space.
 Efficient Management: Techniques for storing, retrieving, and searching vast collections of embeddings.
 Vector Databases: Specialized systems for managing and querying embeddings, including practical considerations for production deployment.
 Real-World Applications: Concrete examples of how embeddings and vector databases are combined with large language models (LLMs) to solve real-world problems.


### Complete Unit 2: “Embeddings and Vector Stores/Databases”, which is:
- [Optional] Listen to the summary podcast episode (https://youtube.com/watch?v=1CC39K76Nqs) for this unit (created by NotebookLM, https://notebooklm.google.com/).
- Read the “Embeddings and Vector Stores/Databases” whitepaper (https://kaggle.com/whitepaper-embeddings-and-vector-stores).
  
### Complete these code labs on Kaggle:
  #### - Build a RAG question-answering system over custom documents - https://www.kaggle.com/code/markishere/day-2-document-q-a-with-rag
  #### - Explore text similarity with embeddings - https://www.kaggle.com/code/markishere/day-2-embeddings-and-similarity-scores
  #### - Build a neural classification network with Keras using embeddings - https://www.kaggle.com/code/markishere/day-2-classifying-embeddings-with-keras

## 💡 What You’ll Learn

Today you will learn about the conceptual underpinning of embeddings and vector databases and how they can be used to bring live or specialist data into your LLM application. You’ll also explore their geometrical powers for classifying and comparing textual data. 

 Reminders and Announcements
-Here is the recording (https://www.youtube.com/watch?v=kpRyiJUUFxY) from this morning’s livestream. We apologize for the live technical issues today! Fortunately our recording did not have the same errors.
-The 2nd livestream is tomorrow with Paige Bailey (https://x.com/DynamicWebPaige) and special guests: Omid Fatemieh, Jinhyuk Lee, Alan Li, Iftekhar Naim, Anant Nawalgaria, Yan Qiao, and Xiaoqi Ren.
-Unfortunately, to ensure a fix to our livestream issues, we need to push back our broadcast time. We'll send another email with updated livestream info soon.
-Be sure to ask all your questions about the podcast, readings, and code lab in the ⁠5dgai-q-and-a channel on Discord. You'll get Kaggle swag if your question is chosen for discussion during the livestream!

## Kaggle GenAI, Tips & Tricks :

https://www.youtube.com/watch?v=v5bhhJ9FD60

# 

## Day 3 Assignments: Agents.

### Authors: Julia Wiesinger, Patrick Marlow and Vladimir Vuskovic
### Introduction
Humans are fantastic at messy pattern recognition tasks. However, they often rely on tools - like books, Google Search, or a calculator - to supplement their prior knowledge before arriving at a conclusion. Just like humans, Generative AI models can be trained to use tools to access real-time information or suggest a real-world action. For example, a model can leverage a database retrieval tool to access specific information, like a customer's purchase history, so it can generate tailored shopping recommendations. Alternatively, based on a user's query, a model can make various API calls to send an email response to a colleague or complete a financial transaction on your behalf. To do so, the model must not only have access to a set of external tools, it needs the ability to plan and execute any task in a self- directed fashion. This combination of reasoning, logic, and access to external information that are all connected to a Generative AI model invokes the concept of an agent, or a program that extends beyond the standalone capabilities of a Generative AI model. This whitepaper dives into all these and associated aspects in more detail.

### Complete Unit 3: “Generative AI Agents”, which is:
- ➡️ [Optional] Listen to the summary podcast episode (https://youtu.be/H4gZd4BCrDQ) for this unit (created by NotebookLM).
- ➡️ Read the “Generative AI Agents” whitepaper (https://www.kaggle.com/whitepaper-agents).
- ➡️ Complete these code labs on Kaggle:
Talk to a database with function calling - https://www.kaggle.com/code/markishere/day-3-function-calling-with-the-gemini-api
Build an agentic ordering system in LangGraph - https://www.kaggle.com/code/markishere/day-3-building-an-agent-with-langgraph/

## 💡 What You’ll Learn

Learn to build sophisticated AI agents by understanding their core components and the iterative development process.
The code labs cover how to connect LLMs to existing systems and to the real world. Learn about function calling by giving SQL tools to a chatbot, and learn how to build a LangGraph agent that takes orders in a café.

# 

## Day 4 Assignments : Solving Domain-Specific Problems Using LLMs
### Authors: Christopher Semturs, Shekoofeh Azizi, Scott Coull, Umesh Shankar and Wieland Holfelder
### Introduction
Large language models (LLMs) have emerged as powerful tools for tackling complex challenges in numerous domains. While early iterations focused on general-purpose tasks, recent developments have highlighted the potential of fine-tuning LLMs to address specific problems within specialized fields. This whitepaper explores these concepts in two distinct domains: cybersecurity and medicine. Each showcases the unique ability of LLMs to enhance existing workflows and unlock new possibilities.
Cybersecurity presents a number of unique challenges for LLMs, including a scarcity of publicly available data, a wide diversity of highly technical concepts, and information about threats that change on a daily basis. Additionally, sensitive use cases, like malware analysis, necessitate specific considerations for model development. We address these challenges by focusing on cybersecurity-specific content and tasks, pairing security-focused language models with a suite of supporting techniques to offer improved performance for vital tasks like threat identification and risk analysis.
In the field of medicine, LLMs face a different set of obstacles, such as the vast and ever- evolving nature of medical knowledge and the need to apply said knowledge in a context- dependent manner that makes accurate diagnosis and treatment a continual challenge.
LLMs like Med-PaLM, customized for medical applications, demonstrate the ability to answer complex medical questions and provide insightful interpretations of medical data, showing potential for supporting both clinicians and patients. Through the lens of these two distinct domains, in this whitepaper we will explore the challenges and opportunities presented by specialized data, technical language, and sensitive use cases. By examining the unique paths taken by SecLM and Med-PaLM, we provide insights into the potential of LLMs to revolutionize various areas of expertise.

### Complete Unit 4: “Domain-Specific LLMs”, which is:
- ➡️  [Optional] Listen to the summary podcast episode (https://youtu.be/b1a4ZOQ8XdI) for this unit (created by NotebookLM).
- ➡️  Read the “Solving Domain-Specific Problems Using LLMs” whitepaper - https://www.kaggle.com/whitepaper-solving-domains-specific-problems-using-llms 
- ➡️  Complete these code labs on Kaggle:
    - [Optional] Use Google Search data in generation. (Note: Grounding with Google Search has been released as a limited launch and is not available in all locations. The EEA, UK, and CH regions will be supported at a later date) - https://www.kaggle.com/code/markishere/day-4-google-search-grounding
    - Tune a Gemini model for a custom task - https://www.kaggle.com/code/markishere/day-4-fine-tuning-a-custom-model

## 💡 What You’ll Learn

In today’s reading, you’ll delve into the creation and application of specialized LLMs like SecLM and MedLM/Med-PaLM, with insights from the researchers who built them.

In the code labs you will learn how to add real world data to a model beyond its knowledge cut-off by grounding with Google Search.  You will also learn how to fine-tune a custom Gemini model using your own labeled data to solve custom tasks.

# 

## Final Assignments: Operationalizing Generative AI on Vertex AI using MLOps.

### Authors: Anant Nawalgaria, Gabriela Hernandez Larios, Elia Secchi, Mike Styer, Christos Aniftos and Onofrio Petragallo
### Introduction
The emergence of foundation models and generative AI (gen AI) has introduced a new era for building AI systems. Selecting the right model from a diverse range of architectures and sizes, curating data, engineering optimal prompts, tuning models for specific tasks, grounding model outputs in real-world data, optimizing hardware - these are just a few of the novel challenges that large models introduce.
This whitepaper delves into the fundamental tenets of MLOps and the necessary adaptations required for the domain of gen AI and Foundation Models. We also examine the diverse range of Vertex AI products, specifically tailored to address the unique demands of foundation models and gen AI-based applications. Through this exploration we uncover how Vertex AI, with its solid foundations of AI infrastructure and MLOps tools, expands its capabilities to provide a comprehensive MLOps platform for gen AI.

## Complete Unit 5: “MLOps for Generative AI”, which is:
  - ➡️ [Optional] Listen to the summary podcast episode (https://youtu.be/k9S6IhiUUj4) for this unit (created by NotebookLM, https://notebooklm.google/).
  - ➡️ Read the “MLOps for Generative AI” whitepaper - https://www.kaggle.com/whitepaper-operationalizing-generative-ai-on-vertex-ai-using-mlops
  - ➡️ No code lab for today! We will do a code walkthrough and live demo of goo.gle/e2e-gen-ai-app-starter-pack (https://goo.gle/e2e-gen-ai-app-starter-pack), a resource created for making MLOps for Gen AI easier and accelerating the path to production. Please go through the repository in advance.

## 💡What You’ll Learn

Discover how to adapt MLOps practices for Generative AI and leverage Vertex AI's tools for foundation models and generative AI applications.

## Bonus day.
- Integrating multimedia data (audio, video, and text).
- Leveraging advanced capabilities.

