# What is LangGraph and Can It Help You Build LLM Agents?

In this post we are going to answer both those questions. Let's start with the first one, and the second will naturally unfold as we go on.

### What is LangGraph?

I'll try to be a little less technical than others who have discussed this. We need a light read sometimes, don't we? Sooo… **LangGraph!** Simply put, LangGraph is a tool that helps you build smarter applications using large language models (LLMs). Think of it as an extension to another tool called **LangChain**.

*"What's that?"* you might ask. Well, **LangChain** is a tool that allows you to create sequences of actions (like a list of steps). **LangGraph**, on the other hand, lets you add loops to these sequences. This means you can ask your language model to repeatedly decide what to do next, making your application more interactive and capable of handling more complex tasks.

Still a bit fuzzy? Let me break it down further.

Imagine **LangChain** as a beginner cook following a simple recipe. The newbie goes step-by-step, adding ingredients in a specific order until the dish is complete. They can't go back and change anything once they've moved to the next step.

**LangGraph**, on the other hand, is like a master chef who can taste the dish at each step, adjust the seasoning, go back to add more ingredients, and tweak the cooking process as needed. The chef can keep refining the dish, going back and forth between steps, until it's perfect. This flexibility allows the chef to adapt and improve the dish continuously, just like **LangGraph** enables continuous decision-making and improvement in building LLM agents.

In essence, **LangGraph** is a step up from **LangChain**. While **LangChain** does the job, **LangGraph** will take your projects to a whole new level. Honestly? It's the tool you didn't know you needed until you see what it can do.

Now, let's dive into a simple example that will clear things up while taking us deeper into **LangGraph**. We'll create a simple chatbot that will respond directly to user messages. Although simple, it will serve the purpose to illustrate the core concepts of building with LangGraph.

For the complete example and code, please refer to the Jupyter notebook in our [GitHub repository](./What-is-LangGraph-and-Can-It-Help-You-Build-LLM-Agents.ipynb).

