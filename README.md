# Langgraph Module 1
## Lesson 1
I learnt why **LangGraph** was created — to make language model workflows more structured and controllable — and how using **graph-based architectures** helps connect multiple agents or tools in a clear, organized way for better reasoning and scalability.

## Lesson 2
In this lesson, I learnt how to build a simple graph in LangGraph by defining nodes, edges, and metadata, and how these components work together to represent a flow of interactions or tasks. I understood that even a basic graph can clearly visualize how data or messages move between agents, making complex workflows easier to design, debug, and extend.

## Lesson 3
I learnt how LangSmith and LangSmith Studio lets you visualize, inspect, and debug your LangGraph agents interactively — you can see the graph’s execution, node-by-node flow, and state changes in real time.

It showed me how integrating with LangSmith gives you deeper observability into agent behavior, which helps you catch errors, understand decisions, and iterate faster.

## Lesson 4 
I learned how to wrap a sequence of operations or “steps” (a chain) into a node in LangGraph so that you can treat that whole sequence as a single unit in the graph, making it easier to integrate more complex logic into your workflow.

## Lesson 5 
I learnt how to use a Router node in LangGraph so that the LLM can dynamically choose which next step (or agent) to take based on state or input.

I understood that routing enables conditional branching — the graph can decide between multiple paths (e.g. tool call vs answer) rather than following a fixed, linear flow.

## Lesson 6 
I learned how to use an Agent node in LangGraph so that the system can autonomously decide which tools to call and which reasoning steps to take — turning the graph into a more dynamic, decision-making actor.

In other words, the graph doesn’t just follow fixed paths — with an Agent node, it can loop, reconsider, call tools, and evolve its behavior based on state and outputs.

## Lesson 7 
I learned how to add memory to an agent node in LangGraph so it can remember past interactions, user context, or state over time.

This makes the agent more conversational and context-aware, allowing it to refer back to earlier messages or decisions rather than starting fresh every time.

## Lesson 8
I learned how to deploy LangGraph agents using LangSmith Deployment, which provides a scalable infrastructure built for long-running tasks. This lesson introduced me to deployment concepts, including creating and connecting to deployments, and managing assistants within the LangGraph ecosystem.




