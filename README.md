# Multi-AI-Agents-using-LangGraph
A simple yet powerful implementation of an Agentic AI workflow using LangGraph, LangChain, and Groq LLM where a Planner Agent decomposes tasks and an Executor Agent produces structured outputs.

# 🤖 Multi-AI Agents using LangGraph  

> A simple yet powerful implementation of an **Agentic AI workflow** using **LangGraph**, **LangChain**, and **Groq LLM** where a Planner Agent decomposes tasks and an Executor Agent produces structured outputs.

---

## 🚀 Project Overview  

This project demonstrates how to build a **Multi-Agent System** using **LangGraph**, where different AI agents collaborate through a graph-based workflow.

The system follows an **Agentic Architecture**:
- User provides a query  
- Planner Agent breaks the task into steps  
- Executor Agent processes those steps  
- Final structured output is generated  

This mirrors how real-world **Agentic AI systems (AutoGPT, CrewAI, Devin, etc.)** operate.

---

## 🧠 Architecture  


User Input
->
Planner Agent (Task Decomposition using LLM)
->
Executor Agent (Processes steps)
->
Final Output

Graph structure is created using **LangGraph nodes and edges** and visualized using Mermaid.

---

## 🛠️ Tech Stack  

- Python  
- LangGraph  
- LangChain  
- Groq LLM (llama-3.1-8b-instant)  
- Google Colab  
- TypedDict for state management  
- Agent-based architecture  

---

## 📦 Features  

✔ Multi-agent workflow using LangGraph  
✔ Planner agent for task decomposition  
✔ Executor agent for step execution  
✔ State management using TypedDict  
✔ Graph visualization using Mermaid  
✔ Uses real LLM via Groq API  
✔ Clean modular architecture  

---

## 📂 Project Structure  

//├── AgentState (TypedDict)
//├── planner_node() # Breaks task into steps
//├── executor_node() # Executes planned steps
//├── LangGraph workflow
//├── Graph compilation
//├── Graph visualization
//└── Final execution


---

## 🧪 Example Run  

**Input:**
How does an Isolation Transformer work?

**Planner Output:**
- Step 1: Primary and Secondary Coil  
- Step 2: Mutual Induction  
- Step 3: Electrical Isolation  

**Final Output:**
Step 1 → Step 2 → Step 3 → Done!

---

## 💡 Why This Project Matters  

This project demonstrates real-world GenAI engineering skills such as:

- Agentic AI systems  
- Task decomposition  
- Graph-based workflows  
- Multi-step reasoning  
- Modular AI architecture  
- LLM orchestration  

These skills are highly relevant for roles like:
- AI Engineer  
- Machine Learning Engineer  
- LLM Engineer  
- Applied GenAI Developer  

---

## 🔮 Future Improvements  

- Add more agents (Researcher, Critic, Refiner)  
- Add tool usage (search, calculator, APIs)  
- Add memory (conversation history)  
- Add RAG (document-based agent)  
- Build Streamlit UI  
- Deploy as web app  

---

## ▶ How to Run  

1. Install dependencies:
```bash
1)pip install langgraph langchain-groq
2)Add your Groq API key
3)Run the notebook
4)Modify input and test agent behavior

