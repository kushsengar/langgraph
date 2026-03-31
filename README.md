🚀 LangGraph Learning Repository
This repository contains my end-to-end journey of learning and implementing LangGraph, starting from fundamentals to advanced workflows.

The goal is simple:

Build a strong, practical understanding of agent workflows, orchestration, and real-world LLM applications.

📌 What is LangGraph?
LangGraph is a framework built on top of LangChain that enables you to design stateful, multi-step workflows (graphs) for LLM-based applications.

Instead of linear chains, LangGraph allows:

Conditional flows

Loops

Parallel execution

Stateful memory across steps

Think of it like:

Moving from simple function calls → to designing intelligent systems.

🧠 What You’ll Learn Here
This repo is structured progressively:

Basics of LangGraph

Sequential workflows

Prompt chaining

Stateful execution

Parallel workflows

Real-world use cases (e.g., essay generation, task orchestration)

📂 Repository Structure
.
├── 0_test_installations.ipynb
├── 1_bmi_workflow.ipynb
├── 2_simple_llm_workflow.ipynb
├── 3_prompt_chaining_workflow.ipynb
├── 4_cricket_workflow_parallel.ipynb
├── 5_upsc_essay_workflow.ipynb
└── README.md
🔍 File Breakdown (With Purpose)
0️⃣ Test Installations
Verifies LangGraph setup

Ensures environment works correctly

👉 If this fails, nothing else will work.

1️⃣ BMI Workflow (Beginner Level)
Simple deterministic workflow

Input → Process → Output

💡 Example:

Input: Height, Weight
Output: BMI + Category
👉 Teaches:

Node creation

Basic graph execution

2️⃣ Simple LLM Workflow
First interaction with LLM inside a graph

💡 Example:

Input: "Explain AI"
Output: LLM-generated explanation
👉 Teaches:

Integrating LLM into nodes

Basic prompt handling

3️⃣ Prompt Chaining Workflow
Multiple LLM steps connected together

💡 Example:

Step 1: Generate topic
Step 2: Expand topic
Step 3: Summarize content
👉 Teaches:

Sequential chaining

Passing state between nodes

4️⃣ Parallel Workflow (Cricket Example)
Executes multiple nodes at the same time

💡 Example:

Input: Match data
Parallel:
  - Batting analysis
  - Bowling analysis
  - Match summary
Output: Combined insights
👉 Teaches:

Parallel execution

Graph branching

5️⃣ UPSC Essay Workflow (Advanced)
Complex, structured content generation

💡 Example:

Input: Essay Topic
Steps:
  - Generate outline
  - Expand sections
  - Add examples
  - Final refinement
👉 Teaches:

Multi-step reasoning

Structured generation

Real-world application

⚙️ Setup Instructions
1. Clone the repository
git clone https://github.com/your-username/langgraph.git
cd langgraph
2. Create virtual environment
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
3. Install dependencies
pip install langchain langgraph openai
4. Set API Key
export OPENAI_API_KEY="your_api_key"
🧪 How to Run
Open notebooks using:

jupyter notebook
Run cells step by step.

🧱 Core Concepts You Should Understand
If you don’t understand these, you’re just copying code:

Node → A function that performs a task

Edge → Connection between nodes

State → Shared data passed across nodes

Graph → Entire workflow structure

⚡ Key Takeaways
LangGraph is not about prompts—it’s about systems design

Real power comes from:

State management

Conditional logic

Multi-step workflows

You’re basically building AI pipelines

🚧 What’s Missing (Be Honest With Yourself)
Right now, this repo is:

Notebook-heavy

Not production-ready

No APIs / UI / deployment

If you want this to stand out:

Convert workflows into APIs (FastAPI)

Add a frontend (React)

Show real-world usage

📈 Future Improvements
Convert workflows into reusable modules

Add real-time applications (chat agents, assistants)

Deploy on cloud (GCP / AWS)

Add evaluation metrics

🤝 Contribution
This is a personal learning repo, but suggestions and improvements are welcome.

📬 Contact
If you're working on similar ideas or want to collaborate, feel free to connect.
