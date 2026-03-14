# Research AI Agent

A LangChain-powered research agent that takes a user query, searches the web and Wikipedia, and returns a structured research summary.

## Features

- Web search via DuckDuckGo
- Wikipedia lookup
- Structured output (topic, summary, sources, tools used)
- Saves results to a `.txt` file

## Setup

1. **Install dependencies**
```bash
   pip install -r requirements.txt
```

2. **Create a `.env` file** with your API keys
```
   OPENAI_API_KEY=your_key_here
   ANTHROPIC_API_KEY=your_key_here
```

3. **Run**
```bash
   python main.py
```

## Stack

- [LangChain](https://www.langchain.com/)
- OpenAI / Anthropic LLMs
- DuckDuckGo Search + Wikipedia
- Pydantic
