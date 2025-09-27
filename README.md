# Dexter's Agentic How-To

I've made this repo to publish my advice and examples of the methods that I use when working with AI agents. I'm using the term "Agent" rather than "LLM" because the public interfaces to LLMs such as the Claude, ChatGPT, and Gemini are now capable of performing elaborate planning of multistep tasks and tool use. The same can be said of coding agents such as Claude Code and Gemini CLI, systems that have extremely broad capabilities in executing code and managing/editing files. 

A central point of my approach to getting agents to perform workflows is that for many purposes, there is no longer any point in creating your own agentic programs using software toolkits such as CrewAI of (other examples TBD). Claude Code, Gemini CLI, and other off-the-shelf agentic frameworks are sufficiently powerful and flexible that your task is simply to analyze the task you wish to accomplish and precisely specify a workflow to accomplish it, in some cases also equipping the agent with appropriate software tools. More than prompt engineering, this is *workflow* engineering.



As of this writing (September 2025), systems like Claude Code and Gemini CLI are generally thought of only as coding assistants. In fact, they are general-purpose systems. In my initial use of Claude Code for non-coding tasks, I found that I needed to strongly prompt it to do tasks directly rather than writing code to accomplish the task. More recently, I find that this coaching is (mostly) no longer neccessary. I see evidence that Anthropic and Google in the early phases of a shift in which they will be marketing theses frameworks for non-coding tasks.

