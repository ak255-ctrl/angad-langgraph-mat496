# Introduction to Langgraph 
# Module 2

## Lesson 1
In this lesson I learned that a state schema defines the structure of data passed between nodes in a LangGraph workflow. It keeps data consistent, type safe, and easier to debug. I practiced creating one using TypedDict or Pydantic. This ensures every node knows exactly what information it’s receiving and updating.

## Lesson 2
In this lesson I learned that state reducers define how updates to each key in the state are handled. They decide whether values are overwritten or combined, like appending lists instead of replacing them. I used Annotated types to specify custom reducers such as operator.add. This helps manage updates safely when multiple nodes modify the same state.

## Lesson 3
In this lesson I learned that multiple schemas can be used in LangGraph to separate input, internal state, and output formats. For example, I can define an InputState for incoming data, an OverallState for processing, and an OutputState for final results. This makes the workflow modular, easier to manage, and clearer in how data flows between stages.

## Lesson 4
In this lesson I learned that managing message history in a graph workflow involves trimming and filtering messages. Trimming removes older messages to stay within model context limits, while filtering keeps only relevant ones. I used functions like trim_messages to shorten history and filter_messages to select specific message types or roles. This keeps the conversation efficient and focused.

## Lesson 5 and 6


In this lesson, I learned how to build a chatbot using LangGraph that summarizes messages and incorporates memory. I implemented a memory saver to retain conversation context and used summarization techniques to condense past interactions. This approach allows the chatbot to maintain relevant information over time, enhancing its ability to handle ongoing conversations effectively.

