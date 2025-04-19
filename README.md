# 🤖 Practical Multi AI Agents and Advanced Use Cases with crewAI

## 📘 Course Overview

[**Practical Multi AI Agents and Advanced Use Cases with crewAI**](https://www.deeplearning.ai/short-courses/practical-multi-ai-agents-and-advanced-use-cases-with-crewai/) is a hands-on course led by João Moura (Founder of CrewAI) that teaches you how to build and deploy intelligent, multi-agent systems using the **crewAI** framework.

The course equips developers and AI practitioners with skills to design, implement, and manage collaborative AI agents for real-world, production-grade use cases—ranging from sales automation to support analytics and content creation.

### 🎯 Key Objectives
- Design agentic workflows with parallel, sequential, and hybrid logic.
- Integrate agents with internal & external systems (e.g., Trello, APIs).
- Leverage multiple LLMs and tools per agent.
- Evaluate and train agent performance using testing & feedback loops.
- Prepare and deploy multi-agent systems for production.


## 📚 Course Content

1. [**Automated Project Planning**](./L1-Automated-Project)
   - Create structured project plans with estimated tasks and milestones.
   - Agents: Planning, Estimation, Resource Allocation

2. [**Project Progress Report (Trello Integration)**](./L2-Project-Progress-Report)
   - Integrate Trello API to fetch real-time updates and generate reports.
   - Tools: Custom Trello fetchers

3. [**Agentic Sales Pipeline**](./L3-Agentic-Sales-Pipeline)
   - Score leads using external data and generate personalized emails.
   - Modular scoring and email writing flows with conditional logic.

4. [**Support Data Insight Analysis**](./L4-Support-Data-Analysis)
   - Analyze CSV-based support data, generate suggestions, tables, charts.
   - Final output: a comprehensive markdown report with visuals.

5. [**Content Creation at Scale**](./L5-Content-Creation)
   - Multi-LLM content generation: monitor news, analyze data, create posts and articles.
   - Output includes blog + platform-specific social posts.

6. [**Production Crew Setup**](./L6-Blogger)
   - Use the CLI to scaffold, configure, and deploy agentic projects.
   - Learn flow management with `crewai` CLI for dynamic execution.


## 📓 Notebooks

> _Click below to explore each real-world agentic use case:_

- [L1: Automated Project Planning](./L1-Automated-Project)
- [L2: Project Progress Report](./L2-Project_Progress_Report)
- [L3: Agentic Sales Pipeline](./L3-Agentic-Sales-Pipeline)
- [L4: Support Data Analysis](./L4-Support-Data-Analysis)
- [L5: Content Creation at Scale](./L5-Content-Creation)
- [L6: Blogger Crew (Production Deployment)](./L6-Blogger)


## 🚀 Getting Started

### 1. Install Requirements

Ensure Python 3.9+ is installed. Then, install dependencies:

```bash
pip install -r requirements.txt
```

### 2. Set Up Environment Variables

Create a `.env` file and add required API keys for:
- OpenAI
- Serper (if used)
- Trello (for integrations)

```bash
OPENAI_API_KEY=your-key
TRELLO_API_KEY=your-key
...
```

### 3. Run Any Notebook

- Open notebooks in Jupyter or VS Code.
- Execute cells sequentially to see agents collaborate.
- Some flows support CLI execution (`crewai run`).


## 🔗 Resources and References

- [Course Homepage](https://www.deeplearning.ai/short-courses/practical-multi-ai-agents-and-advanced-use-cases-with-crewai/)
- [CrewAI Documentation](https://docs.crewai.com/)
- [OpenAI API Docs](https://platform.openai.com/docs)
- [Serper API](https://serper.dev)


## 🛠 Helpers & Utils

The course includes `helper.py` for:

- `load_env()` – Load `.env` variables securely into the environment.
- CLI-friendly execution and configuration management.
- Trello tool setup for project integration.
- Code for usage tracking and cost estimation.

Also includes:
- `requirements.txt` – All necessary dependencies.
- YAML configs (under `config/`) for defining agents and tasks.


Enjoy building real-world, scalable agent systems with **crewAI**! 🚀