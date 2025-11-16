# Kaggle-Capstone-Project
It shows the full created study planner AI agent
# 📘 Study Planner AI — Multi-Agent Learning & Productivity Assistant

A smart, automated, multi-agent system that creates optimized study plans, decomposes tasks, balances workload, and provides weekly analytics — built using the Agent Development Kit.

---

## 🚀 Features

- 📥 **Task Intake Agent**  
  Converts natural language tasks into structured JSON.

- 🧩 **Task Decomposition Agent**  
  Breaks large tasks into subtasks with estimated durations.

- 📅 **Scheduling Agent**  
  Generates a balanced 7-day schedule, based on deadlines & complexity.

- 📊 **Analytics Agent**  
  Tracks workload, consistency, subject distribution, weekly insights.

- 🧠 **Supervisor Agent**  
  Routes tasks, maintains global context, orchestrates agent workflow.

---
## 🛠️ Architecture Overview
User Input → Task Intake Agent
↓
Task Decomposition Agent
↓
Scheduling Agent
↓
Analytics Agent ← Shared Memory
↓
Final Study Plan Output

See `ARCHITECTURE.md` for diagrams and details.

## 📂 Project Structure

study-planner-ai/

│
├── agents/
│ ├── supervisor_agent.py
│ ├── intake_agent.py
│ ├── decomposition_agent.py
│ ├── scheduling_agent.py
│ └── analytics_agent.py

│
├── tools/
│ ├── calendar_tools.py
│ ├── storage.py
│ └── analytics_tools.py


│
├── notebooks/
│ └── study_planner_notebook.ipynb
│


├── docs/
│ ├── ARCHITECTURE.md
│ ├── AGENT_DESCRIPTIONS.md
│ └── ROADMAP.md



│
├── main.py
├── requirements.txt
├── LICENSE
└── README.md

## 🔧 Installation & Setup

```bash
git clone https://github.com/USERNAME/study-planner-ai.git
cd study-planner-ai
pip install -r requirements.txt

Demo

User enters tasks

Agents classify + decompose

Scheduler generates 7-day plan

Analytics produce insights

System outputs personalized plan

Screenshots + diagrams recommended here.

💡 Why Agents?

Understand and structure natural language tasks

Negotiate deadlines and workloads

Adapt schedules dynamically

Think reason, plan, and evaluate

Allow modular, scalable task automation

🛠 Technologies Used

Python

Gemini Models

Agent Development Kit (ADK)

Kaggle Notebook

JSON-based memory

Custom scheduling algorithm

🧭 Future Improvements

See docs/ROADMAP.md for full vision.

Key goals:

Calendar syncing

Real-time Web UI

Group study planning

Adaptive learning

Voice-driven inputs
## 🛠️ Architecture Overview

