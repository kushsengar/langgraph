# 🚀 LangGraph Learning Repository

> From basics → advanced workflows using LangGraph

---

## 📌 Overview

This repository documents my hands-on journey of learning **LangGraph** by building progressively complex workflows.

Instead of dumping theory, this repo focuses on:
- Practical implementations  
- Real workflow patterns  
- Incremental learning  

---

## ⚡ What is LangGraph?

LangGraph is a framework built on top of LangChain for designing **stateful, multi-step workflows (graphs)** for LLM applications.

### 🔥 Why it matters
- Traditional chains → linear  
- LangGraph → dynamic, stateful systems  

---

## 🧠 Key Capabilities

- 🔀 Conditional flows  
- 🔁 Loops  
- ⚡ Parallel execution  
- 🧾 Stateful memory across steps  

---

## 📂 Project Structure

├── 0_test_installations.ipynb
├── 1_bmi_workflow.ipynb
├── 2_smpt_chaining_workflow.ipynb
├── 4_cricket_workflow_parallel.ipynb
├── 5_upsc_essay_workflow.ipynb
└── README.md

## 📘 Learning Progression

### 🟢 Beginner

#### 1. BMI Workflow

* Basic graph structure
* Deterministic logic

**Flow:**

```
Input → Process → Output
```

---

#### 2. Simple LLM Workflow

* First LLM integration
* Prompt → Response

---

### 🟡 Intermediate

#### 3. Prompt Chaining Workflow

* Multi-step reasoning
* Output of one node → input to another

**Flow:**

```
Idea → Expansion → Summary
```

---

### 🔴 Advanced

#### 4. Parallel Workflow (Cricket Analysis)

* Multiple nodes executed simultaneously

**Flow:**

```
          → Batting Analysis
Input →   → Bowling Analysis → Merge → Output
          → Match Summary
```

---

#### 5. UPSC Essay Workflow

* Structured long-form generation
* Multi-stage refinement

**Flow:**

```
Topic → Outline → Sections → Examples → Final Essay
```

---

## ⚙️ Setup


git clone https://github.com/your-username/langgraph.git
cd langgraph

python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows

pip install langchain langgraph openai


---
## 🔑 Environment Variables

export OPENAI_API_KEY="your_api_key"

## ▶️ Run

```bash
jupyter notebook
```

---

## 🧱 Core Concepts (Don’t Skip This)

| Concept | Meaning                         |
| ------- | ------------------------------- |
| Node    | A function that performs a task |
| Edge    | Connection between nodes        |
| State   | Shared data across nodes        |
| Graph   | Complete workflow               |

---

## ⚡ Key Takeaways

* LangGraph is about **system design**, not just prompts
* Real power comes from:

  * State management
  * Multi-step workflows
  * Conditional execution

---

## 🚧 Current Limitations

Let’s be honest:

* Notebook-based (not production-ready)
* No APIs / UI / deployment
* Mostly learning-focused

---

## 📈 Future Improvements

* Convert workflows into APIs (FastAPI)
* Build a frontend interface
* Deploy on cloud (GCP / AWS)
* Add real-world use cases
* Add evaluation + metrics

---

## 🤝 Contributions

This is a personal learning repository, but suggestions are welcome.

---
