# LangChain_SelfAsk_MultiToolAgent
LangChain with Self-Ask Agent

### Self-Ask with Search Agent:

## Definition:

This approach allows the AI to ask itself follow-up questions when it doesn't immediately know the answer. It performs a recursive questioning process to break down complex queries into smaller, more manageable ones.
Once the AI generates these follow-up questions, it performs an external search (e.g., through Google or an internal database) to gather the necessary information before formulating a response.
How it works:

- Step 1: Receive a complex question.
- Step 2: The agent identifies sub-questions or follow-up questions.
- Step 3: It performs a search or fetches answers to these questions from external resources (like a web search).
- Step 4: The answers are aggregated to provide a complete response.
Key points:

Emphasizes question decomposition.
Relies on external search for sub-questions.
Useful for answering open-ended or broad questions where the answer is not immediately available.
Example:

Original question: “How many moons does Jupiter have?”
Sub-question: “What is Jupiter?” (search)
Sub-question: “What are moons?” (search)
Finally, it retrieves the answer: "Jupiter has 79 moons."
