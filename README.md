# learn-lab-agentic-ai

## LangChain
Framework for developing apps powered by LLMs. Chainable / Composable tools, memory, actions and agents
  -- Used with python and virtual env (TS is possible)

**Deep agents** - have access to more built-in tools than agents (which would have to be implemented as tools), like - write_todos (break down for research), grep, file access. And it can spawn subagents

**LangSmith** -Trace and inspect agent calls to LLMs

https://docs.langchain.com/oss/python/langchain/quickstart#langchain-agents


## Run local models
Installed Ollama (brew install)
Pull a model and run (Ollama pull llama3, ollama run llama3)
(Uninstalled - too resource intensive)

## LangChain ecosystem
- LangChain - Build agents with any model of choice
- LangGraph - Orchestration framework for agents (not just LangChain)
- LangSmith - Provides Observability and Deployment

## LangGraph
- LLM bound with tools -> decides to process as natural text or call a tool. Doesn't actually call.
- Add a tool condition to actually call the tool if LLM decides to
- ReAct arch - Route the tool output back to LLM
