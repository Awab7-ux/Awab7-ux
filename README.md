<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:0EA5E9,100:818CF8&height=240&section=header&text=Awab%20Imad&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20Backend%20%26%20Full-Stack%20Developer&descSize=20&descAlignY=60" alt="Awab Imad - Software Engineer, Backend and Full-Stack Developer" width="100%"/>

<a href="https://github.com/Awab7-ux">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=900&color=38BDF8&center=true&vCenter=true&width=760&lines=Backend+%26+Full-Stack+Developer;Python+%7C+Flask+%7C+FastAPI+%7C+REST+APIs;React+%26+React+Native+%2B+TypeScript;AI+%2F+LLM+Integration+(OpenAI+%7C+Groq+%7C+Whisper);Multi-Tenant+SaaS+%7C+JWT+%7C+RBAC;Docker+%7C+Kubernetes+%7C+CI%2FCD" alt="Typing animation"/>
</a>

<br/>

<a href="https://www.linkedin.com/in/awab-imad">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:awabmadalhwrywork@outlook.com">
<img src="https://img.shields.io/badge/Email-Contact_Me-06B6D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email"/>
</a>
<a href="https://github.com/Awab7-ux">
<img src="https://img.shields.io/badge/GitHub-Awab7--ux-181717?style=for-the-badge&logo=github" alt="GitHub"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/Status-Open_to_Work-22C55E?style=flat-square&logo=statuspage&logoColor=white" alt="Open to work"/>
<img src="https://img.shields.io/badge/Location-Egypt_%7C_Gulf-0EA5E9?style=flat-square" alt="Location"/>
<img src="https://img.shields.io/badge/B.Sc.-Computing_2025-818CF8?style=flat-square" alt="B.Sc. Computing"/>
<img src="https://komarev.com/ghpvc/?username=Awab7-ux&label=Profile+Views&color=0EA5E9&style=flat-square" alt="Profile views"/>

</div>

---

## 01. About Me

Computing graduate (B.Sc., 2025) and aspiring Software Engineer specializing in **backend and full-stack development**. I built **three end-to-end projects** with Python/Flask, React, REST APIs, PostgreSQL, JWT authentication and AI/LLM integration, including a **bilingual telemedicine platform with 56 registered users**.

**What I enjoy engineering:**

- 🔹 Backend systems, REST APIs and scalable application architectures.
- 🔹 Multi-tenant SaaS platforms, authentication and role-based access control.
- 🔹 AI-powered applications: LLM integration, Whisper speech-to-text, semantic search.
- 🔹 React and React Native apps with bilingual (Arabic / English) interfaces.
- 🔹 Docker, Kubernetes, CI/CD pipelines and cloud deployment.

**Currently focused on:** AI engineering · distributed application architecture · Cloud & DevOps.

🎯 Open to **Software Engineer · Backend Developer · Full-Stack Developer · AI Engineer** roles, especially at startups in Egypt and the Gulf region.

---

## 02. Featured Projects

### 🏥 Sahatak (صحتك) — Bilingual Telemedicine Platform
<sub>2025 – 2026 · Web & Mobile</sub>

<div align="center">

<img src="https://img.shields.io/badge/Flask-REST_API-0EA5E9?style=for-the-badge&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/React_Native-TypeScript-818CF8?style=for-the-badge&logo=react&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI-Whisper_%2B_GPT-412991?style=for-the-badge&logo=openai&logoColor=white"/>

<a href="https://github.com/Awab7-ux/Sahatak-Telemedicine-App2">
<img src="https://img.shields.io/badge/Explore_Sahatak-Repository-0EA5E9?style=for-the-badge&logo=github&logoColor=white" alt="Sahatak repository"/>
</a>

</div>

A bilingual (Arabic / English) digital healthcare platform that connects patients and doctors through remote consultations, appointment booking, medical records and AI-assisted preliminary symptom assessment.

**System Architecture**

```mermaid
flowchart TD
    P["Patient Mobile App<br/>React Native · Expo · TypeScript"]
    W["Web Portal<br/>Patient · Doctor · Admin"]
    P --> API
    W --> API
    API["Flask REST API<br/>SQLAlchemy · JWT · RBAC"]
    API --> DB[("MySQL / SQLite")]
    API --> AI["OpenAI API<br/>GPT · Whisper"]
    API --> J["Jitsi Meet<br/>Video Consultations"]
    API --> CHAT["Real-time Chat<br/>Files · Typing · Read receipts"]
```

**Engineering highlights**

- Patient and doctor dashboards with authentication and role-based access control (**56 registered users**).
- Real-time patient–doctor chat (file sharing, typing indicators, read receipts) and Jitsi Meet video consultations.
- Appointment booking with email notifications, medical reports, vital-signs tracking and clinic/pharmacy maps; booking confirmation takes about **1–3 seconds on web** and about **1 second on mobile**.
- Bilingual OpenAI symptom-assessment assistant with Whisper voice input (**50+ queries processed**), plus a React Native / TypeScript mobile app on the same APIs (internal testing, pre-release).

**AI Symptom Assessment Workflow**

```mermaid
flowchart LR
    A["Patient Symptoms"] --> B{"Input Method"}
    B -->|Text| D["GPT Triage"]
    B -->|Voice| C["OpenAI Whisper"]
    C --> D
    D --> E{"Preliminary Assessment"}
    E --> F["Telemedicine"]
    E --> G["In-Person Care"]
    E --> H["Emergency Care"]
```

<sub>The assistant gives preliminary guidance only, not a medical diagnosis. Figures are historical project metrics, not live counters.</sub>

**Tech:** `Python` `Flask` `SQLAlchemy` `JavaScript` `React Native` `TypeScript` `OpenAI API` `Whisper` `Jitsi Meet`

---

### ⚖️ Lexera — AI Contract Intelligence Platform
<sub>2026</sub>

<div align="center">

<img src="https://img.shields.io/badge/AI-Powered_Contract_Intelligence-818CF8?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Architecture-Multi--Tenant-0EA5E9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Deployed-Railway_%7C_Vercel-22C55E?style=for-the-badge"/>

</div>

A multi-tenant SaaS platform that simplifies legal contract management with AI-powered risk analysis, semantic search and automated renewal alerts.

**Architecture**

```mermaid
flowchart TD
    U["Users"] --> FE["React + TypeScript<br/>Vercel"]
    FE --> API["Flask REST API<br/>Railway"]
    API --> AUTH["JWT Authentication + RBAC<br/>Admin · Manager · Viewer"]
    API --> TENANT["Organization-Level Data Isolation"]
    API --> WORKER["Celery + Redis<br/>Upstash"]
    WORKER --> AI["Groq-hosted LLMs<br/>Risk Analysis"]
    WORKER --> EMB["Sentence Transformers<br/>Local Embeddings"]
    AI --> DB[("PostgreSQL + pgvector<br/>Neon")]
    EMB --> DB
    TENANT --> DB
```

**Engineering highlights**

- Multi-tenant Flask backend with **organization-scoped data isolation**, JWT authentication and **three roles** (admin, manager, viewer).
- Automated backend tests for authentication and tenant isolation.
- Celery/Redis background processing for **three workflows**: LLM risk analysis, speech-to-text transcription and renewal alerts.
- Semantic search with PostgreSQL/pgvector, Groq-hosted LLMs and local sentence-transformer embeddings.
- REST APIs and a React/TypeScript front end, deployed across four services: Railway, Neon, Upstash and Vercel.

<img src="https://skillicons.dev/icons?i=python,flask,react,ts,vite,tailwind,postgres,redis,docker,vercel&theme=dark" width="100%" alt="Lexera technologies"/>

<a href="https://github.com/Awab7-ux/Lexera">
<img src="https://img.shields.io/badge/View_Source_Code-Lexera-818CF8?style=for-the-badge&logo=github" alt="Lexera source code"/>
</a>

---

### ☁️ CloudOps Platform — Deploy, Monitor & Manage Cloud Applications
<sub>2026 · Active Development</sub>

A cloud engineering platform designed to simplify application deployment, automate testing through CI/CD, and manage containerized applications using Docker and Kubernetes.

**Delivery Pipeline**

```mermaid
flowchart LR
    DEV["Developer"] --> GIT["GitHub"]
    GIT --> CI["GitHub Actions"]
    CI --> TEST["Automated Tests"]
    TEST --> BUILD["Docker Build"]
    BUILD --> COMPOSE["Docker Compose"]
    COMPOSE --> K8["Kubernetes / kind<br/>Manifests prepared"]
    K8 -.-> MON["Prometheus / Grafana<br/>Roadmap"]
    GIT -.-> TF["Terraform<br/>Roadmap"]
```

**Implemented**

- FastAPI backend (**4 API endpoints**, **5 automated tests**) and a React/TypeScript/Vite frontend served via Nginx.
- Containerized with Docker and Docker Compose, plus **1 GitHub Actions CI workflow** for backend and frontend testing.
- Kubernetes manifests prepared (1 planned backend replica, 1 GiB PV/PVC for SQLite on kind).

<sub>**Status:** deployment to Kubernetes is not yet completed. Uses SQLite and has no authentication yet. **Roadmap:** Terraform, Prometheus and Grafana.</sub>

<img src="https://skillicons.dev/icons?i=python,fastapi,react,ts,vite,docker,nginx,kubernetes,githubactions,sqlite&theme=dark" width="100%" alt="CloudOps technologies"/>

<a href="https://github.com/Awab7-ux/cloudops-platform">
<img src="https://img.shields.io/badge/Explore_CloudOps-Repository-2563EB?style=for-the-badge&logo=github" alt="CloudOps repository"/>
</a>

---

### 📊 PMS — Project Management System
<sub>Active Development</sub>

A multi-tenant project management SaaS inspired by Jira, Asana and Trello, built to manage organizations, teams, projects and collaborative workflows.

```mermaid
flowchart TD
    SA["Super Admin"] --> ORG["Organizations"]
    ORG --> OWNER["Organization Owners"]
    OWNER --> TEAM["Teams"]
    TEAM --> PROJECT["Projects"]
    PROJECT --> TASK["Tasks & Subtasks"]
    ORG --> BACK["Flask Backend"]
    BACK --> AUTH["Authentication · JWT"]
    BACK --> RBAC["Role-Based Access"]
    BACK --> DB["SQLAlchemy · Migrations"]
```

<sub>The backend foundation is implemented; some product modules and UI features remain planned or prototyped.</sub>

<img src="https://skillicons.dev/icons?i=python,flask,postgres,redis,docker,nginx,bootstrap&theme=dark" width="100%" alt="PMS technologies"/>

<a href="https://github.com/Awab7-ux/PMS">
<img src="https://img.shields.io/badge/Explore_PMS-Repository-06B6D4?style=for-the-badge&logo=github" alt="PMS repository"/>
</a>

---

## 03. Other Projects

| Project | Description | Technologies |
|---|---|---|
| [Accounts](https://github.com/Awab7-ux/accounts) | Accounts REST service, CI and security headers | Python, Docker |
| [Tax Calculator DevOps](https://github.com/Awab7-ux/tax-calculator-devops-capstone) | Tested tax service and Kubernetes manifests | Flask, Docker, Kubernetes |
| [CI/CD Final Project](https://github.com/Awab7-ux/ci-cd-final-project) | Automated testing and container builds | Node.js, Docker |
| [Full-Stack Capstone](https://github.com/Awab7-ux/xrwvm-fullstack_developer_capstone) | Full-stack application and deployment configuration | Django, Docker |
| [Online Course](https://github.com/Awab7-ux/onlinecourse-final-project) | Online learning platform with assessments | Django |
| [Backend Development Capstone](https://github.com/Awab7-ux/Back-end-Development-Capstone) | Concert website backend | Django |
| [Medical Appointment](https://github.com/Awab7-ux/med_appt) | Doctor appointment booking frontend | JavaScript, HTML, CSS |

---

## 04. Technical Skills

<div align="center">

<img src="https://skillicons.dev/icons?i=python,js,ts,html,css,postgres&theme=dark" alt="Languages"/>
<br/>
<img src="https://skillicons.dev/icons?i=flask,fastapi,react,vite,tailwind,bootstrap&theme=dark" alt="Frameworks"/>
<br/>
<img src="https://skillicons.dev/icons?i=mysql,sqlite,redis,docker,kubernetes,nginx&theme=dark" alt="Data and infra"/>
<br/>
<img src="https://skillicons.dev/icons?i=githubactions,git,github,linux,vscode,vercel,gcp&theme=dark" alt="DevOps and tools"/>

</div>

| Area | Skills |
|---|---|
| **Languages** | Python · JavaScript · TypeScript · SQL |
| **Backend** | Flask · FastAPI · REST APIs · SQLAlchemy · Alembic · JWT · RBAC · WebSockets (Flask-SocketIO) · Celery |
| **Frontend & Mobile** | HTML · CSS · React · React Native · TypeScript · Tailwind CSS |
| **Data** | PostgreSQL · pgvector · Redis · Database Migrations · Semantic Search |
| **AI & LLM** | OpenAI API · Groq API · Whisper · Sentence-Transformer Embeddings · LLM Integration |
| **DevOps & Tools** | Docker · Kubernetes · Nginx · Git · GitHub · CI/CD · Railway · Vercel · Neon · Upstash |
| **Testing** | pytest · Automated Backend Testing · API Integration · System Design |

---

## 05. Engineering Principles

| Principle | My Approach |
|---|---|
| 🔐 Security First | Keep secrets server-side and enforce authorization at API boundaries. |
| 🏢 Tenant Isolation | Scope organization data at every query and test isolation boundaries. |
| 🧱 Maintainable Architecture | Separate routers, services, repositories and schemas. |
| 🚀 Reliable Delivery | Automated tests, CI workflows and containerized environments. |
| 🤖 Practical AI | Integrate AI into real workflows with clear limitations and safeguards. |
| 📝 Transparency | Clearly distinguish implemented features from prototypes and roadmap items. |

---

## 06. Certifications

<div align="center">

<a href="https://www.credly.com/badges/1b787526-1c64-41a5-9687-d5ea45afe68c">
<img src="https://img.shields.io/badge/IBM-Generative_AI_Engineering-0F62FE?style=for-the-badge&logo=ibm&logoColor=white" alt="IBM Generative AI Engineering"/>
</a>
<a href="https://www.credly.com/badges/db59f61d-ce17-44b6-aac2-22ac3f78406a">
<img src="https://img.shields.io/badge/IBM-DevOps_%26_Software_Engineering-0F62FE?style=for-the-badge&logo=ibm&logoColor=white" alt="IBM DevOps and Software Engineering"/>
</a>
<a href="https://www.credly.com/badges/50ee3989-fa66-4d57-a522-22a7f1e35f52">
<img src="https://img.shields.io/badge/IBM-CI%2FCD-0F62FE?style=for-the-badge&logo=ibm&logoColor=white" alt="CI/CD"/>
</a>
<br/>
<img src="https://img.shields.io/badge/IBM-Full_Stack_Software_Developer-0F62FE?style=for-the-badge&logo=ibm&logoColor=white" alt="IBM Full Stack"/>
<img src="https://img.shields.io/badge/Linux_Foundation-OpenAPI_Fundamentals-003366?style=for-the-badge&logo=linuxfoundation&logoColor=white" alt="OpenAPI Fundamentals"/>
<img src="https://img.shields.io/badge/Anthropic-AI_Fluency-D97757?style=for-the-badge" alt="Anthropic AI Fluency"/>
<br/>
<img src="https://img.shields.io/badge/Google_Cloud-Generative_AI_Leader-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Cloud Generative AI Leader"/>
<img src="https://img.shields.io/badge/Cisco-Python_Essentials_1_%26_2-049FD9?style=for-the-badge&logo=cisco&logoColor=white" alt="Cisco Python Essentials"/>

</div>

<details>
<summary><b>📜 Full certification list</b></summary>

<br/>

**Artificial Intelligence & Generative AI**
- IBM Generative AI Engineering Professional Certificate
- IBM Generative AI Essentials for Software Developers V2
- IBM AI Engineering Professional Certificate (V3)
- AI Capstone Project with Deep Learning (IBM)
- Z DevOps Testing Fundamentals (IBM)
- Python for Data Science, AI & Development (IBM)
- AI Fluency: Framework & Foundations (Anthropic)
- Generative AI Leader Professional Certificate (Google Cloud)

**DevOps, CI/CD & Infrastructure**
- IBM DevOps and Software Engineering Professional Certificate (IBM / Coursera, 2026)
- Continuous Integration & Continuous Delivery, CI/CD (IBM)
- Docker Practical Course (Devopsarea)
- Kubernetes CKA Badge (Credly) · Kubernetes CKA: Services and Networking

**Cloud Computing**
- Essential Google Cloud Infrastructure: Foundation & Core Services (Google Cloud)
- Preparing for Google Cloud Certification: Cloud Engineer (Google Cloud)
- Intel Partner Technical Pro: Cloud DevOps Competency (Intel)

**Software Engineering & Full-Stack Development**
- IBM Full Stack Software Developer Professional Certificate
- IBM Front-End Developer Professional Certificate
- IBM Back-End Development Professional Certificate
- Full-Stack Web Developers and Back-End Developers (IBM)
- Apply Software Engineering Principles to Drive Reliability (IBM)
- Full Stack Software Developer Assessment (IBM)
- System Design and Architecture (Manara)

**Databases, APIs & Security**
- Databases (Manara)
- OpenAPI Fundamentals, LFEL1011 (Linux Foundation)
- for Software Development Managers, LFD125 (Linux Foundation)

**Programming**
- Python Essentials 1 and 2 (Cisco)

</details>

<sub>Verify credentials through the linked Credly pages. These are professional certificates and course-completion credentials, not proctored vendor certification exams.</sub>

---

## 07. Education

🎓 **Bachelor of Science (B.Sc.) in Computing** — Future University, Khartoum, Sudan · 2021 – 2025
🌐 Languages: Arabic, English

---

## 08. GitHub Analytics

<div align="center">

<img width="49%" src="https://github-readme-stats.shion.dev/api?username=Awab7-ux&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0A192F&title_color=38BDF8&icon_color=06B6D4&text_color=CBD5E1" alt="GitHub statistics"/>
<img width="49%" src="https://github-readme-stats.shion.dev/api/top-langs/?username=Awab7-ux&layout=compact&theme=tokyonight&hide_border=true&bg_color=0A192F&title_color=38BDF8&text_color=CBD5E1" alt="Most used languages"/>

<br/><br/>

<img width="70%" src="https://streak-stats.demolab.com/?user=Awab7-ux&theme=tokyonight&hide_border=true&background=0A192F&ring=06B6D4&fire=38BDF8&currStreakLabel=38BDF8" alt="GitHub streak"/>

<br/><br/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Awab7-ux&bg_color=0A192F&color=38BDF8&line=2563EB&point=E6F1FF&area=true&hide_border=true" alt="Contribution activity graph"/>

<br/><br/>

<img width="100%" src="https://github-profile-trophy.vercel.app/?username=Awab7-ux&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7" alt="GitHub trophies"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Awab7-ux/Awab7-ux/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Awab7-ux/Awab7-ux/output/github-snake.svg"/>
  <img alt="Animated GitHub contribution snake" src="https://raw.githubusercontent.com/Awab7-ux/Awab7-ux/output/github-snake-dark.svg" width="100%"/>
</picture>

</div>

---

## 09. Let's Connect

<div align="center">

**I build software that solves problems, connects systems and creates meaningful impact.**

Open to engineering opportunities, technical discussions and collaborations.

<br/>

<a href="https://www.linkedin.com/in/awab-imad">
<img src="https://img.shields.io/badge/LinkedIn-Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
</a>
<a href="mailto:awabmadalhwrywork@outlook.com">
<img src="https://img.shields.io/badge/Email-Send_a_Message-06B6D4?style=for-the-badge&logo=microsoftoutlook" alt="Email"/>
</a>
<a href="https://github.com/Awab7-ux">
<img src="https://img.shields.io/badge/GitHub-Explore_My_Work-181717?style=for-the-badge&logo=github" alt="GitHub"/>
</a>

<br/><br/>

<sub>Designed and engineered by Awab Imad · Always building. Always learning.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:818CF8,50:0EA5E9,100:0F172A&height=140&section=footer" width="100%" alt="footer"/>

</div>
