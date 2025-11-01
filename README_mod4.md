# Intro to Langgraph
# Module 4

## Lesson 1 
1) I learnt how to add nodes using the add_node function and to go from one node to another using the add_edge function. 
2) After seeing in the first example a linear path from node A to node D, we tweak the code and run it with nodes B and C parallel to each other.
3) It is also shown how to use a reducer to make sure that the state updates from running B and C parallel to each over give no error.
4) We then understand how to use custom reducers that sort the values in the state after each update

## Lesson 2
1) I learnt how to set the output schema of the sub-graph.
2) Then we learn how to add the sub-graph to the parent graph by defining our parent graph state and passing the cleaned logs to the sub-graphs.
3) We must also use a reducer because both sub-graphs will be writing into the same processed logs.

## Lesson 3
1) Learned about the map reduce pattern, which is a way to handle big or complex tasks by first breaking them into smaller parts during the map step and then joining all the results together in the reduce step to get one final output.
2) Created a map node that works on one small part of the input at a time, for example summarizing each paragraph or processing one section separately before moving to the next.
3) Built a reduce node that takes all the small results made by the map node and combines them into one complete and meaningful answer.
4) Connected the map and reduce nodes in a LangGraph workflow so that the map step spreads the work across many parts and the reduce step collects everything back into one flow.
5) Understood that this method helps make large language model projects more efficient, easier to handle, and better suited for long texts or large amounts of data.

## Lesson 4
1. Learned how to make a research assistant workflow that studies a topic step by step by asking questions, collecting information, and writing a full summary in the end.

2. Created different types of nodes such as an analyst that comes up with useful questions, an expert that finds answers from sources, and a writer that explains what was found in a clear way.

3. Saw how the assistant can use online tools like search and document retrieval to look for information, check different sources, and keep improving its answers as it learns more.

4. Learned that several analysts or experts can work together in the same workflow, each focusing on one part of the topic, and then their results are combined into one complete report.

5. Understood that this setup helps build a smart assistant that does real research, not just quick question and answer, but a deeper process of gathering, thinking, and explaining.
