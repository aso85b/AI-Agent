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

```bash
pip install openai langchain langchain-community tiktoken
