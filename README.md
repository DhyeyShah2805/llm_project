---

# 🧠 Agentic AI with LangGraph & MCP — Crash Course (Part 1)

A hands-on crash course on building **Agentic AI workflows** using **LangGraph**, **LangChain**, and **Model Context Protocol (MCP)** 

---

## 📌 Overview

This project focuses on how to build AI agents using graph-based architectures. It focuses on:

* Using **LangGraph** to structure agent flows as graphs
* Enhancing agents with **tools**, **memory**, and **streaming**
* Implementing **ReAct agents**
* Adding **human-in-the-loop** feedback
* Building an **MCP server** for persistent agent context

---

## 🚀 Features

* 🧩 Build AI workflows using LangGraph’s node/edge architecture
* 🛠️ Integrate tools like calculators or web search into agents using **Tavily Search API.**
* 🧠 Add memory and context to conversations
* 📡 Enable streaming responses
* 🧑‍⚖️ Human feedback handling
* 🖥️ Implement a custom MCP server

---

## 🛠️ Tech Stack

* **Python 3.10+**
* [LangGraph](https://github.com/langchain-ai/langgraph)
* [LangChain](https://github.com/langchain-ai/langchain)
* OpenAI API (or any LLM provider)
* FastAPI (for MCP server)

---

## 📂 Project Structure

```
├── 1_simple_graph.ipynb             # Intro to LangGraph
├── 3_chatbot.ipynb                  # Basic chatbot with graph
├── 4_tool_call.ipynb                # Adding tools to agent
├── 5_tool_call_agent.ipynb          # Tool + ReAct logic
├── 6_tool_call_agent_memory.ipynb   # Adding memory
├── 7_streaming_agent.ipynb          # Enable streaming responses
├── 8_human_feedback_agent.ipynb     # Human feedback
├── 9_MCP_server.ipynb               # Build MCP server from scratch
└── .env                             # Environment variables
```

---

## ⚙️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/krishnaik06/Agentic-LanggraphCrash-course.git
cd Agentic-LanggraphCrash-course
```

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

3. **Set up environment variables:**

Copy `.env.sample` to `.env` and add your OpenAI API key:

```env
OPENAI_API_KEY=your-api-key-here
```

---

## 🧪 Run Notebooks

Open any notebook in VS Code or Jupyter and run sequentially to follow the full course progression.

Recommended order:

1. `1_simple_graph.ipynb`
2. `3_chatbot.ipynb`
3. `4_tool_call.ipynb`
4. `5_tool_call_agent.ipynb`
5. `6_tool_call_agent_memory.ipynb`
6. `7_streaming_agent.ipynb`
7. `8_human_feedback_agent.ipynb`
8. `9_MCP_server.ipynb`

---

## 📚 Learning Resources

* [📺 YouTube Course](https://youtu.be/dIb-DujRNEo)
* [LangGraph Docs](https://langchain-ai.github.io/langgraph/)
* [LangChain Docs](https://docs.langchain.com/)
* [MCP Intro Blog](https://medium.com/@vamshiginna1606/langgraph-101-build-your-first-agentic-ai-workflow-step-by-step-for-beginners-b9a1a0cec59a)

---

## ✨ Credits

Course by [Krish Naik](https://www.youtube.com/@KrishNaik).
GitHub Repo: [krishnaik06/Agentic-LanggraphCrash-course](https://github.com/krishnaik06/Agentic-LanggraphCrash-course)

---

## 📜 License

MIT License

---

Let me know if you want a shorter version, a more beginner-friendly tone, or if you’re publishing it on GitHub and want badges, demo links, or a contributing guide.
