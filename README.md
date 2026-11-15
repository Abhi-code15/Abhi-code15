<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,45:1e3a8a,100:7c3aed&height=240&section=header&text=Abhishek%20Tiwari&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%20Engineer%20%E2%80%A2%20Backend%20Developer%20%E2%80%A2%20Machine%20Learning&descAlignY=58&descSize=18" alt="Abhishek Tiwari" />

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3200&pause=900&color=A78BFA&center=true&vCenter=true&width=860&height=45&lines=Building+AI+agents+from+first+principles+%F0%9F%A4%96;Shipping+backend+systems+with+Node%2C+Express+%26+PostgreSQL+%E2%9A%99%EF%B8%8F;Turning+sensor+data+into+predictions+with+ML+%F0%9F%93%88;Request+%E2%86%92+API+%E2%86%92+Model+%E2%86%92+Insight+%F0%9F%9A%80)](https://git.io/typing-svg)

![Profile Views](https://komarev.com/ghpvc/?username=Abhi-code15&label=PROFILE+VIEWS&color=7c3aed&style=flat-square)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-abhishek015-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishek015)
[![Email](https://img.shields.io/badge/Email-Get_in_touch-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:abhishekstu15@gmail.com)
![Status](https://img.shields.io/badge/Open_to-Internships_%26_Collabs-22c55e?style=flat-square)

</div>

---

## 👋 About Me

I'm **Abhishek**, a B.Tech student at **NIT Silchar** (Electronics & Instrumentation Engineering, 2028) who builds at the intersection of **AI, backend engineering and machine learning**.

My engineering background gives me a habit most CS students don't pick up early: I think in **signals, sensors and systems**. That's why my projects range from a **predictive-maintenance ML pipeline** to an **LLM agent engine** to **production-style REST backends**, and why I prefer building the hard parts myself rather than hiding behind a framework.

```python
class Abhishek:
    role       = "AI + Backend Engineer (in the making)"
    education  = "B.Tech EIE, NIT Silchar · 2024-2028"
    languages  = ["Python", "C++", "JavaScript", "SQL"]
    ai_ml      = ["LightGBM", "XGBoost", "Scikit-learn", "RAG", "MCP", "Ollama"]
    backend    = ["Node.js", "Express", "FastAPI", "PostgreSQL", "JWT", "Docker"]
    building   = ["EngineSense", "Autonomous AI Agent Engine", "Agentra AI"]
    mindset    = "Understand it from scratch, then ship it properly."
```

---

## 🏗️ How I Think About Systems

```mermaid
flowchart LR
    U([User / Client]) --> API[REST API<br/>Node · Express · FastAPI]
    API --> AUTH{{JWT Auth<br/>Validation}}
    AUTH --> DB[(PostgreSQL)]
    API --> ML[ML Service<br/>LightGBM · XGBoost]
    API --> AG[AI Agent Layer<br/>LLM · Tools · Memory]
    AG --> LLM[Ollama · OpenAI-compatible API]
    AG --> RAG[(Knowledge Base<br/>RAG)]
    AG --> MCP[External Tools<br/>MCP]
    ML --> DASH[Streamlit · React Dashboards]
    style AG fill:#7c3aed,color:#fff
    style ML fill:#1e3a8a,color:#fff
    style API fill:#0d1117,color:#fff
```

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔧 [EngineSense](https://github.com/Abhi-code15/EngineSense)
**Predictive Maintenance for Engines** · `ML`

A machine learning platform that predicts engine faults from sensor data and serves them through an interactive dashboard.

- Pipeline over **12.5K+ engine records** and **6 sensor parameters**, with leakage-free preprocessing and stratified train/val/test splits
- Tuned **LightGBM** reached **94.68% fault recall**, with **48.63% fewer missed faults** than the Random Forest baseline (5-fold CV, holdout-tested)
- **Streamlit** app with model selection, validated inference and prediction history
- **27 automated unit & integration tests** with pytest

`Python` `LightGBM` `XGBoost` `Scikit-learn` `Pandas` `Streamlit` `pytest`

[🌐 Live Demo](https://enginesense-ai.streamlit.app/) · [📂 Code](https://github.com/Abhi-code15/EngineSense)

</td>
<td width="50%" valign="top">

### 🤖 [Autonomous AI Agent Engine](https://github.com/Abhi-code15/ai-agent-from-scratch)
**LLMs → Multi-Agent Systems** · `AI` · 🔨 *in progress*

An agent engine built layer by layer, covering LLM fundamentals, retrieval and standardized tool use, with no agent framework underneath.

- Local assistant on **Ollama + Qwen 2.5** with conversational memory, system prompts and an **OpenAI-compatible API**
- **RAG pipeline** that grounds answers in custom knowledge sources
- **Model Context Protocol (MCP)** integration so the agent can reach external tools and resources
- ReAct-style loop, function calling and streaming, documented in an engineering logbook

`Python` `Ollama` `Qwen 2.5` `RAG` `MCP` `Function Calling`

[📂 Code](https://github.com/Abhi-code15/ai-agent-from-scratch)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧩 [Agentra AI](https://github.com/Abhi-code15/Agentra-Ai)
**AI-Powered Workflow Automation** · `AI + Backend`

A full-stack platform where users describe a task and an LLM-driven backend plans and executes it through tool calling, with results shown in a structured UI.

- **Prompt engineering and tool calling** connect user intent to real actions
- Modular **Express** services separate request handling, orchestration and AI logic
- **React + Vite** interface for managing AI-assisted workflows
- Containerized with **Docker** for reproducible setup

`React` `Vite` `Node.js` `Express` `PostgreSQL` `LLM Tool Calling` `Docker`

[📂 Code](https://github.com/Abhi-code15/Agentra-Ai)

</td>
<td width="50%" valign="top">

### 💸 [Paylog](https://github.com/Abhi-code15/Paylog)
**Smart Finance & UPI Payment Tracker** · `Backend`

A full-stack finance platform that joins expense tracking with a QR-based UPI payment workflow.

- **QR scanning and UPI deep-linking** to start payments from any compatible UPI app
- Payment-confirmation flow that records outcomes next to expenses
- **RESTful APIs** for income, expenses and transactions on **PostgreSQL**
- **JWT authentication** with strict user-scoped data access

`React` `Node.js` `Express` `PostgreSQL` `JWT` `REST`

[🌐 Live Demo](https://paylog-flow.onrender.com/) · [📂 Code](https://github.com/Abhi-code15/Paylog)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### ⚡ [WattWise](https://github.com/Abhi-code15/WattWise)
**Real-Time Energy Analytics Platform** · `Backend + Real-time`

A real-time analytics backend that ingests consumption readings, processes them and streams insights to a live dashboard. **Socket.IO** drives event-driven updates, **Prisma + PostgreSQL** form the data layer with **Zod** request validation, and the whole stack (frontend, API, database) is **Dockerized** and tested with **Vitest & Supertest**.

`React` `Vite` `Node.js` `Express` `PostgreSQL` `Prisma` `Socket.IO` `Zod` `Docker` `Vitest`

[📂 Code](https://github.com/Abhi-code15/WattWise)

</td>
</tr>
</table>

---

## 🧰 Tech Stack

<div align="center">

**Languages & Core**

<img src="https://skillicons.dev/icons?i=py,cpp,c,js,postgres,mongodb&perline=6&theme=dark" alt="languages and databases" />

**Backend & Web**

<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,react,vite,tailwind,prisma,socketio&perline=8&theme=dark" alt="backend and web" />

**AI / ML**

<img src="https://skillicons.dev/icons?i=tensorflow,sklearn,pandas,numpy,jupyter&perline=5&theme=dark" alt="ai ml" />

![LightGBM](https://img.shields.io/badge/LightGBM-02A9E0?style=for-the-badge)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5424?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-0EA5E9?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP-6E56CF?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**Tools & Deployment**

<img src="https://skillicons.dev/icons?i=git,github,docker,postman,vercel,linux&perline=6&theme=dark" alt="tools" />

</div>

**Core CS:** Data Structures & Algorithms · OOP · DBMS · Operating Systems · Computer Networks

---

## 💼 Experience

**🏭 Siemens Scholar Trainee** · *Siemens India, Nashik* · May – Jun 2026

- Completed the **Siemens Mechatronics Systems Certification Program (Level 1)** and **Business & Manufacturing Excellence (BMEX)** under the Siemens Scholarship Program
- Contributed to the ideation and prototype design of **BhoomiAI**, an **IoT- and AI-enabled smart agriculture platform** delivering soil insights, crop recommendations and data-driven farming decisions
- Explored **Industry 4.0** and industrial automation workflows: connected systems, process data and automation for manufacturing productivity

---

## 🏆 Achievements & Leadership

| | |
|:---|:---|
| 🎓 **Siemens Scholar (2024)** | 1 of 300 students chosen from 10,000+ government engineering college applicants across India |
| 🥇 **HMEL Energy Quest 3.0** | One of 30 national winners |
| 🧠 **Problem Solving** | 300+ problems solved across coding platforms (DSA) |
| 🤖 **NERDS Robotics Club, NIT Silchar** | Core member; led robotics projects and club events reaching 200+ students |
| 🛠️ **INSEES, NIT Silchar** | Technical & event management; departmental workshops for 100+ students |

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Abhi-code15&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abhi-code15&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />

<img src="https://streak-stats.demolab.com/?user=Abhi-code15&theme=tokyonight&hide_border=true" alt="GitHub streak" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Abhi-code15/Abhi-code15/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Abhi-code15/Abhi-code15/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/Abhi-code15/Abhi-code15/output/github-snake-dark.svg" />
</picture>

</div>

---

## 🤝 Let's Build Something

I'm open to **internships, AI / backend / ML engineering roles and collaborations**. If you're working on agents, ML products or backend systems, I'd love to talk.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishek015)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abhishekstu15@gmail.com)

*"Understand it from scratch. Ship it properly."*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,55:1e3a8a,100:0d1117&height=110&section=footer" alt="footer" />

</div>
