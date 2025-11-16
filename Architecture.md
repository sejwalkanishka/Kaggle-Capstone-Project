# System Architecture

Study Planner AI uses a modular, multi-agent system.

## Agent Workflow

1. **User Input** → Task Intake Agent  
2. Converts to JSON → Task Decomposition Agent  
3. Breaks into subtasks → Scheduling Agent  
4. Creates 7-day study plan → Analytics Agent  
5. Generates weekly insights → Output  

---

## Data Flow Diagram

User  
→ Intake Agent  
→ Decomposition Agent  
→ Scheduling Agent  
→ Analytics Agent  
→ Result

---

## Components

### Supervisor Agent
Central router and controller.

### Sub-Agents
- Intake Agent — NLP → JSON  
- Decomposition Agent — Breaks into subtasks  
- Scheduling Agent — Time allocation  
- Analytics Agent — Reports & insights  
