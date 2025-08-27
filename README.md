# AIAgents

# Agent Lab 🧪  
*A collection of experiments in building AI Agents.*

---

## About This Repository


The goal is not just to showcase prototypes, but to build a reference collection that evolves toward **scalable, enterprise-grade agent architectures**.

---

## Experiments

### 1. Conversational Agent with Context Awareness
[🔗 View Notebook](https://github.com/Sidharth1327/AIAgents/blob/main/ai-agents/Conversational_agent_with_context_awareness.ipynb)  

A minimal conversational agent that maintains **dialogue history across multiple turns** using LangChain’s memory utilities.  
- **Tech stack:** LangChain, OpenAI GPT (gpt-4o-mini), ChatMessageHistory, RunnableWithMessageHistory  
- **Key idea:** Keeps track of prior messages to create coherent, context-aware conversations.  
- **Future direction:** Persistent memory (Redis/Postgres), summarization memory, RAG integration, tool-use, and monitoring for production readiness.  

### 2. AI Powered Simple Data Analysis Agent
[🔗 View Notebook](https://github.com/Sidharth1327/AIAgents/blob/main/ai-agents/AI_powered_Data_Analysis_Ageny.ipynb)  

An introductory agent that enables **natural language interaction with a dataset**, translating plain-text questions into structured data analysis.  
- **Tech stack:** OpenAI GPT (gpt-4o-mini), Pandas, LangChain Agents  
- **Key idea:** Combines a language model with data manipulation tools to let users query and explore a dataset without coding.  
- **Future direction:** Real-world dataset integration (SQL/CSV/APIs), query translation into SQL/Pandas, richer analytics (visualizations, forecasting), explainability of executed operations, and deployment via Streamlit/Gradio for accessibility.  
