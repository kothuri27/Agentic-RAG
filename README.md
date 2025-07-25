# 🤖 Agentic RAG: Retrieval-Augmented Generation with LangChain & LangGraph

This project implements an **Agentic Retrieval-Augmented Generation (RAG)** workflow using [LangChain](https://www.langchain.com/), [LangGraph](https://github.com/langchain-ai/langgraph), and [ChatGroq](https://groq.com/). It supports document ingestion, vector-based retrieval, tool use, and intelligent agent decision-making through a structured LangGraph workflow.

---

## 🚀 Features

- 🔗 **Two independent vector stores**:
  - One for **LangGraph** 
  - One for **LangChain** 

- 🧠 **Agentic Decision Making**:
  - Uses ChatGroq LLM (`qwen-qwq-32b`)
  - Dynamically chooses to retrieve, rewrite query, or directly answer

- 🛠️ **Tool-based Retrieval**:
  - LangChain `retriever_tool` interface for seamless agent integration

- 📖 **Relevance Grading**:
  - LLM-based scoring to decide whether retrieved documents are relevant

- 🔄 **Query Rewriting**:
  - Rephrases questions when initial results are irrelevant

- 🧵 **LangGraph Workflow**:
  - State-based transitions between `agent`, `retrieve`, `generate`, and `rewrite`

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone <your-repo-url>
cd Agentic-RAG


