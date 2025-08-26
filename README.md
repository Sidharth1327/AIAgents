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