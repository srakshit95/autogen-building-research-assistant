## Title: Building a Research Assistant using AutoGen Multi-Agent Framework
#### Description:
This notebook demonstrates how to build a collaborative multi-agent AI Research Assistant using Microsoft’s AutoGen framework. It sets up a simulated groupchat environment where different specialized agents (e.g., Engineer, Planner, User Proxy) work together to execute research-related tasks using GPT-4o.

#### Key components include:

AutoGen Agent Definitions: Sets up roles such as UserProxyAgent, AssistantAgent, and a GroupChatManager.

LLM Configuration: Uses OpenAI’s GPT-4o model via config_list_from_json.

Planning & Execution Workflow: One agent plans tasks, another executes code (e.g., Python or Shell), and a human-in-the-loop agent approves actions.

Interactive Multi-Agent Chat: Simulates collaborative decision-making and task execution through structured dialogue and code generation.

This is ideal for exploring agent-based orchestration, LLM planning/execution separation, and building advanced AI copilots or assistants for research workflows.
