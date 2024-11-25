# AI Agent using LangChain and OpenAI

This Python script creates an AI agent powered by OpenAI's GPT model, utilizing LangChain for efficient prompt management and response generation. The agent interacts with users in a real-time, chat-like format, answering queries and providing conversational responses.

## Key Features:

- **OpenAI Integration**: Uses OpenAI's `gpt-3.5-turbo` or `gpt-4` model via the OpenAI API to generate natural language responses.
- **LangChain**: Leverages LangChain to manage prompt templates and chains for querying the OpenAI model.
- **Retry Logic**: Automatically retries requests if the OpenAI API rate limit is exceeded (handles `RateLimitError`).
- **Interactive Chat**: Provides a real-time conversational interface, allowing users to ask questions with an option to quit at any time.

## Requirements:

- `openai`: Required for integrating with OpenAI's API.
- `langchain`: Manages prompt templates and chains for querying OpenAI.
- `langchain-community` and `tiktoken`: Required for specific functionalities related to the language model.

## Installation:

To install the necessary dependencies, run the following command:

- bash
pip install openai langchain langchain-community tiktoken

##---------------

## Hugging_Face:
Hugging Face is an AI and NLP platform that provides tools, models, and datasets for developers and researchers. Its primary focus is on simplifying the development and deployment of machine learning models, especially in NLP. Key components include:

- Transformers Library:
A collection of pre-trained models for tasks like text classification, translation, summarization, and more.
Supports popular architectures like GPT, BERT, RoBERTa, and T5.
- Datasets:
Provides a hub for various datasets in NLP and machine learning. The datasets library allows easy access and preprocessing.
- Hugging Face Hub:
A central repository for hosting, sharing, and collaborating on machine learning models, datasets, and spaces.
- Inference API:
Simplifies the process of deploying models for real-world applications, with endpoints for serving models via API.
- Community and Open Source:
Hugging Face emphasizes openness, collaboration, and community-driven development.


## Using Hugging Face and LangChain Together

Hugging Face and LangChain are complementary. Developers often integrate Hugging Face's pre-trained models and APIs into LangChain-based applications to leverage powerful NLP capabilities with structured logic and memory management.
