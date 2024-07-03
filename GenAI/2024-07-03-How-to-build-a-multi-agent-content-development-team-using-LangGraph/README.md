# How to build a multi-agent content development team using LangGraph

Hey! I'm back.

Building a multi-agent content development team can be complex, especially when using advanced tools like LangGraph.

But don't worry!

In this post, I'll guide you step-by-step through creating a simple yet effective multi-agent team with LangGraph.

We'll revisit some key concepts to ensure a solid understanding, making the process smoother even if you're new to LangGraph.

Let's dive in and master this powerful tool together!

## What is LangGraph?

"This again?" One might ask.

Yeah, bear with me, let's fix this concept once and for all!

Well, as I was saying, LangGraph is an extension of LangChain, whose main objective is creating agent and multi-agent projects.

It adds the ability to create cyclical flows while providing developers a high degree of control, which is - obviously - very important for creating custom agents and flows.

I think that's enough theoretical jibber jabber for now. Let's start building something!

I don't know if you all read my first blog post about LangGraph. If you didn’t and want to check out some basics, here it is: [What is LangGraph and can it help you build LLM agents?](link_to_blog_post)

## Building - not the best, but - pretty good content development team

With this project, I want to show you all that we can improve almost any process in depth and quality by leveraging multiple agents with specialized skills.

Why is that?

Well, having every agent focus and specialize only in a specific task allows more customizability, better separation of concerns, and, of course, further development as the project grows. LangGraph is no place for a jack of all trades.

## The content development team

Our humble team consists of three agents:

- **Researcher** - This fella is specialized in web search. He will deliver in-depth research on a given topic. No questions asked.
- **Editor** - The role of this agent is to be annoying to his buddy, the researcher. The editor will review the content brought by the researcher agent and demand more whenever he thinks it's needed. He will also provide some query tips.
- **Writer** - This is the last agent of our flow, responsible for writing about the suggested topic using the context available from the previously mentioned agents.

For the complete example and code, please refer to the Jupyter notebook in our [GitHub repository](./how-to-build-a-multi-agent-content-development-team-using-LangGraph.ipynb).
