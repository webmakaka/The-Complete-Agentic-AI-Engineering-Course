# [Ed Donner] The Complete Agentic AI Engineering Course [ENG, 2025]

**original src:**  
https://github.com/ed-donner/agents

**models:**  
https://github.com/marketplace/models

<br/>

### 6 week journey to code and deploy AI Agents with OpenAI Agents SDK, CrewAI, LangGraph, AutoGen and MCP

![Autonomous Agent](img/course.png)

<br/>

# 6-Week AI Agent Learning Roadmap

### Week 1: Foundations

- **Make an Agentic Workflow**: Learn the core mechanics of agent execution loops.
- **Agents and Agentic Patterns**: Explore common design patterns like reflection and planning.
- **Orchestrating LLMs**: Understand how to prompt, steer, and manage large language models.
- **Autonomy and Tools**: Learn how agents autonomously select and execute external functions.
- **Project 1**: Build your personal career agent.

### Week 2: OpenAI Agents SDK

- **Understand OpenAI Agents SDK concepts**: Master the fundamentals of the OpenAI Agents SDK framework.
- **Project 2: an SDR**: Develop an SDR (Sales Development Representative) agent.
- **Tools vs Agents Guardrails**: Implement safety measures and execution limits for autonomous agents.
- **Project 3: Deep Research**: Create a Deep Research agent.
- **Project 3: Deep Research app**: Deploy the Deep Research agent into a functional application.

### Week 3: CrewAI

- **Understand CrewAI Concepts**: Learn how multi-agent role-playing frameworks operate.
- **Build a Crew Agent**: Create individual specialized agents with distinct roles and goals.
- **Project 4: Stock Picker**: Build a Stock Picker multi-agent system.
- **Project 5: Developer Agent**: Build a Developer Agent to automate coding tasks.
- **Project 5: Engineering Team**: Scale your developer agents into a collaborative Engineering Team.

### Week 4: LangGraph

- **Understand LangGraph concepts**: Master cyclical graphs and state management for complex workflows.
- **Build a LangGraph Agent**: Implement stateful multi-agent architectures using nodes and edges.
- **Tools, memory, web searches**: Add persistent memory and real-time search capabilities to graphs.
- **Project 6: Sidekick**: Develop a Sidekick agent assistant.
- **Project 6: Sidekick improvements**: Optimize and refine the Sidekick agent's graph topology.

### Week 5: AutoGen

- **Understand AutoGen concepts**: Explore event-driven multi-agent conversation frameworks.
- **AutoGen Agent Chat**: Build conversational patterns between multiple autonomous agents.
- **AutoGen Core**: Learn the foundational messaging and event routing layers of the framework.
- **AutoGen Core - distributed**: Scale agents across distributed environments and networks.
- **Project 7: Agent Creator**: Build an Agent Creator that dynamically spawns other agents.

### Week 6: MCP (Model Context Protocol)

- **Agentic Architecture and MCP**: Understand the protocol standard for connecting agents to data sources.
- **Building an MCP Server and Client**: Create custom data connectors and client-side integrations.
- **Multiple Local and Remote MCP servers**: Orchestrate complex systems utilizing various distributed data layers.
- **Project 8: AI Equity Traders**: Develop AI Equity Traders leveraging real-time protocol data.
- **Project 8: AI Equity Traders In Action**: Deploy and monitor the AI Equity Traders in a live simulated environment.

<br/>

## Setup instructions for Linux

<br/>

```shell
$ cd setup
$ uv sync
$ source .venv/bin/activate
```

<br/>

```shell
# $ cp .env.template .env
```

<br/>

```shell
# $ python diagnostics.py
```

<br/>

## OpenAI Compatible URLs

<br/>

```python
ANTHROPIC_BASE_URL = "https://api.anthropic.com/v1/"
DEEPSEEK_BASE_URL = "https://api.deepseek.com/v1"
GEMINI_BASE_URL = "https://generativelanguage.googleapis.com/v1beta/openai/"
GITHUB_BASE_URL = "https://models.github.ai/inference"
GROQ_BASE_URL = "https://api.groq.com/openai/v1"
GROK_BASE_URL = "https://api.x.ai/v1"
OPENROUTER_BASE_URL = "https://openrouter.ai/api/v1"
OLLAMA_BASE_URL = "http://localhost:11434/v1"
```
