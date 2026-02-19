# agentic-ai
# Key Takeaways:

## Agents & Tools: 
The fundamental building blocks for defining capabilities and reasoning. Clear instructions and docstrings are paramount.

## Runners & Session Services: 
The engine and memory management system that orchestrate agent execution and maintain conversational context.

## Delegation: 
Designing multi-agent teams allows for specialization, modularity, and better management of complex tasks. Agent description is key for auto-flow.

## Session State (ToolContext, output_key): 
Essential for creating context-aware, personalized, and multi-turn conversational agents.

## Callbacks (before_model, before_tool): 
Powerful hooks for implementing safety, validation, policy enforcement, and dynamic modifications before critical operations (LLM calls or tool execution).

## Flexibility (LiteLlm): 
ADK empowers you to choose the best LLM for the job, balancing performance, cost, and features.
