 # LangChain Learning Journey

A collection of hands-on notebooks and examples demonstrating the core concepts of LangChain, and Agentic AI.

This repository contains practical implementations completed while learning the LangChain ecosystem, including model integrations, tools, agents, memory, middleware, and conversational AI workflows.

---

## Topics Covered

- Model Integration
  - ChatGroq (Llama 3.3 70B)
  - Google Gemini

- Prompt Engineering

- Chat Models
  - Single prompts
  - Multi-turn conversations

- Tools
  - Creating custom tools with `@tool`
  - Tool calling

- Agents
  - Building AI agents with `create_agent`
  - Tool execution

- Memory
  - Conversation memory
  - `InMemorySaver`

- Middleware
  - `SummarizationMiddleware`
  - Context management


---

## Technologies Used

- Python 3.12
- LangChain
- LangGraph
- LangChain Groq
- Google Generative AI
- python-dotenv
- Jupyter Notebook

---

## Repository Structure

```
updatedlangchain/
│
├── 1-model-integration.ipynb
├── 2-chat-models.ipynb
├── 3-tools.ipynb
├── 4-agents.ipynb
├── 5-memory.ipynb
├── 6-middleware.ipynb
└── ...
```

---

## Setup

Clone the repository

```bash
git clone https://github.com/noorfatima1028/langchain.git
cd langchain
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate it

Linux/macOS

```bash
source .venv/bin/activate
```

Windows

```bash
.venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Create a `.env` file

```env
GROQ_API_KEY=your_api_key
GOOGLE_API_KEY=your_api_key
```

Run the notebooks using Jupyter Notebook or VS Code.

---

## Notes

Some middleware examples use `SummarizationMiddleware`.

When using ChatGroq, certain middleware demonstrations may produce `tool_use_failed` errors because of current limitations in Groq's tool-calling behavior during automatic summarization. The implementation is included for learning purposes.

---

## Learning Objectives

- Understand LangChain fundamentals
- Build AI agents with tools
- Work with conversational memory
- Explore middleware and context management
- Learn LangGraph workflows
- Practice Agentic AI development

---

## Author

**Noor Fatima**

GitHub: https://github.com/noorfatima1028
