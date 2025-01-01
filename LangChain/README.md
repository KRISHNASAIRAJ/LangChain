# Introduction

LangChain is a framework for developing applications powered by language models.

LangChain is a framework designed to assist in building applications that leverage Large Language Models (LLMs).

It provides abstractions and tools to make it easier to work with LLMs, particularly for complex workflows and tasks that require chaining multiple steps or integrating multiple data sources. LangChain helps in creating sophisticated applications such as chatbots, question answering systems, summarization tools, or data pipelines, using LLMs like OpenAI's GPT, LLaMA, and other transformer-based models.

![LangChain](https://python.langchain.com/svg/langchain_stack_112024_dark.svg)

LangChain implements a standard interface for large language models and related technologies, such as embedding models and vector stores, and integrates with hundreds of providers.

A chat model is a language model that is trained to generate responses that are contextually relevant to a given conversation.

The model is trained on a large corpus of text data, which includes a wide range of conversations and topics. The model learns to generate responses that are coherent and relevant to the conversation, and that can be used to answer questions or provide information.

Chains: A chain is a sequence of actions, where each action (or step) is typically a call to an LLM, an API, or some other process. Chains allow you to compose multiple tasks together to build more complex behaviors.

Agents: These are components that can dynamically decide what action to take based on the input. Agents are used for tasks like reasoning, answering questions, or executing tasks that require context-specific decisions, such as calling external APIs or databases.