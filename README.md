 <div align="center">

<!-- ANIMATED HERO -->
<img src="https://capsule-render.vercel.app/api?type=waving&height=250&color=0:071426,45:0B3C8C,100:06B6D4&text=AWAB%20IMAD&fontColor=FFFFFF&fontSize=62&fontAlignY=38&desc=Software%20Engineer%20%7C%20Backend%20%26%20Full-Stack%20%7C%20AI%20Systems&descSize=17&descAlignY=60&animation=fadeIn" width="100%" alt="Awab Imad animated profile banner"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=2800&pause=900&color=38BDF8&center=true&vCenter=true&width=850&lines=Building+Intelligent+Software+Systems;Designing+Scalable+Backend+Architectures;Engineering+AI-Integrated+Applications;Turning+Complex+Ideas+Into+Real+Products;Exploring+Cloud+%26+DevOps+Engineering" alt="Animated engineering introduction"/>

<br/>

<a href="https://www.linkedin.com/in/awab-imad-5a541637b">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:awabpasta@gmail.com">
<img src="https://img.shields.io/badge/Email-Contact_Me-06B6D4?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://github.com/Awab7-ux">
<img src="https://img.shields.io/badge/GitHub-Awab7--ux-181717?style=for-the-badge&logo=github" alt="GitHub"/>
</a>

<br/><br/>

**AI-Integrated Systems · Backend Engineering · Full-Stack Development · Cloud & DevOps**

<sub>Building reliable software. Engineering practical solutions. Learning continuously.</sub>

</div>

---

## 01. About Me

I'm a Computer Science graduate and Software Engineer interested in designing and building complete software systems, from backend architecture and REST APIs to modern web and mobile applications.

My work focuses on combining solid software engineering practices with practical AI integration to solve real-world problems.

**What I enjoy engineering:**

- Backend systems, RESTful APIs and scalable application architectures.
- Multi-tenant SaaS platforms, authentication and role-based access control.
- AI-powered applications, LLM integration and intelligent workflows.
- React and React Native applications with bilingual interfaces.
- Containerization, CI/CD pipelines and cloud infrastructure.

**Currently focused on:** AI engineering, distributed application architecture, Cloud and DevOps.

Open to Software Engineer, Backend Engineer, Full-Stack Developer and AI Engineer opportunities, as well as meaningful engineering collaborations.

---

## 02. Featured Engineering Projects

### 🏥 Sahatak (صحتك) — Integrated Telemedicine Platform

<div align="center">

<a href="https://github.com/Awab7-ux/Sahatak-Telemedicine-App2">
<img src="https://img.shields.io/badge/Explore_Sahatak-Repository-0EA5E9?style=for-the-badge&logo=github&logoColor=white" alt="Sahatak repository"/>
</a>

**Connecting patients, doctors and healthcare services through technology.**

</div>

Sahatak is a bilingual digital healthcare platform designed to improve access to medical services through remote consultations, appointment booking, medical records and AI-assisted preliminary symptom assessment.

The engineering challenge involves coordinating mobile and web clients with a shared backend and external services.

**System Architecture**

```mermaid
flowchart TD
    P["Patient Mobile App<br/>React Native · Expo · TypeScript"]
    W["Web Portal<br/>Patient · Doctor · Admin"]
    P --> API
    W --> API
    API["Flask REST API<br/>SQLAlchemy · JWT"]
    API --> DB[("MySQL / SQLite")]
    API --> AI["OpenAI API<br/>GPT · Whisper"]
    API --> J["Jitsi Meet<br/>Video Consultations"]
    API --> CHAT["HTTP Polling<br/>Patient-Doctor Messaging"]
```

**Core capabilities**

| Area | Features |
|---|---|
| Patient experience | Registration, profiles, doctor discovery and appointment booking |
| Medical records | Health records, care summaries and prescriptions |
| Consultations | Jitsi Meet video consultations |
| Communication | Patient-doctor messaging, notifications and file sharing |
| AI integration | Preliminary symptom assessment and voice transcription |
| Healthcare services | Pharmacy, clinic locator and checkup packages |
| Accessibility | Arabic / English, RTL support and Calm Mode |

**Project components**

- [Patient Mobile App](https://github.com/Awab7-ux/Sahatak-Telemedicine-App2/tree/main/sahatak-mobile) — React Native, Expo and TypeScript.
- [Web Portal & Team Backend](https://github.com/sahataksudan-collab/Sahatak) — HTML, JavaScript, Bootstrap and Flask.
- [Companion Repository](https://github.com/Awab7-ux/Sahatak-Telemedicine-App2) — companion backend and web implementation.

**AI Symptom Assessment Workflow**

```mermaid
flowchart TD
    A["Patient Symptoms"] --> B{"Input Method"}
    B -->|Text| D["GPT Triage"]
    B -->|Voice| C["OpenAI Whisper"]
    C --> D
    D --> E{"Preliminary Risk Assessment"}
    E --> F["Telemedicine"]
    E --> G["In-Person Care"]
    E --> H["Emergency Care"]
```

Voice input is transcribed through Whisper and processed using a language-aware GPT prompt. The system provides preliminary guidance, not a professional medical diagnosis.

**Engineering highlights**

- 3 coordinated application components.
- 56 historical registered users.
- 50+ historical AI symptom-assessment queries.
- JWT authentication and Jitsi integration.
- HTTP Polling instead of WebSockets for messaging.

<sub>Figures are historical project metrics, not live counters. The mobile APK has not been publicly released.</sub>

---

### ⚖️ Lexera — AI Contract Intelligence SaaS

<div align="center">

<img src="https://img.shields.io/badge/AI-Powered_Contract_Intelligence-818CF8?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Architecture-Multi--Tenant-0EA5E9?style=for-the-badge"/>

</div>

Lexera is a multi-tenant SaaS platform designed to simplify legal contract management through AI-powered risk analysis, semantic search and automated renewal alerts.

**Architecture**

```mermaid
flowchart TD
    U["Users"] --> FE["React + TypeScript"]
    FE --> API["Flask REST API"]
    API --> AUTH["JWT Authentication + RBAC"]
    API --> TENANT["Organization-Level Isolation"]
    API --> WORKER["Celery + Redis"]
    WORKER --> AI["LLM Contract Analysis"]
    WORKER --> EMB["Sentence Transformers"]
    AI --> DB[("PostgreSQL + pgvector")]
    EMB --> DB
    TENANT --> DB
```

**Key engineering features**

- Multi-tenant architecture with organization-scoped data isolation.
- JWT authentication and role-based permissions.
- AI-assisted contract risk analysis and missing-clause detection.
- Semantic search using PostgreSQL and pgvector.
- Local sentence-transformer embeddings to reduce external API costs.
- Background processing using Celery and Redis.
- Speech-to-text voice notes and renewal alerts.

**Technology stack**

<img src="https://skillicons.dev/icons?i=python,flask,react,ts,vite,tailwind,postgres,redis,docker,vercel&theme=dark" width="100%" alt="Lexera technologies"/>

**Deployment:** Railway · Neon · Upstash · Vercel

<a href="https://github.com/Awab7-ux/Lexera">
<img src="https://img.shields.io/badge/View_Source_Code-Lexera-818CF8?style=for-the-badge&logo=github" alt="Lexera source code"/>
</a>

---

### ☁️ CloudOps — Cloud Infrastructure & Deployment Platform

<sub>Active Development</sub>

A cloud infrastructure and deployment management platform built to explore production-style DevOps workflows through a FastAPI backend and React dashboard.

**Delivery Pipeline**

```mermaid
flowchart LR
    DEV["Developer"] --> GIT["GitHub"]
    GIT --> CI["GitHub Actions"]
    CI --> TEST["Automated Tests"]
    TEST --> BUILD["Docker Build"]
    BUILD --> COMPOSE["Docker Compose"]
    COMPOSE --> K8["Kubernetes / kind"]
    K8 -.-> MON["Prometheus / Grafana<br/>Roadmap"]
    GIT -.-> TF["Terraform<br/>Roadmap"]
```

**Implemented engineering components**

- FastAPI backend with layered architecture.
- React and TypeScript dashboard.
- Docker images and Docker Compose.
- Nginx frontend serving.
- GitHub Actions CI workflows.
- Kubernetes manifests for local kind.
- Approximately 240 pytest test functions.

**Technology stack**

<img src="https://skillicons.dev/icons?i=python,fastapi,react,ts,vite,docker,nginx,kubernetes,githubactions,sqlite&theme=dark" width="100%" alt="CloudOps technologies"/>

**Current limitations:** SQLite database, no authentication yet, and some dashboard pages use labeled demo data.

**Roadmap:** Terraform, Prometheus and Grafana monitoring.

<a href="https://github.com/Awab7-ux/cloudops-platform">
<img src="https://img.shields.io/badge/Explore_CloudOps-Repository-2563EB?style=for-the-badge&logo=github" alt="CloudOps repository"/>
</a>

---

### 📊 PMS — Project Management System

<sub>Active Development</sub>

A multi-tenant project management SaaS platform inspired by Jira, Asana and Trello, designed to help organizations manage teams, projects and collaborative workflows.

**System hierarchy**

```mermaid
flowchart TD
    SA["Super Admin"]
    SA --> ORG["Organizations"]
    ORG --> OWNER["Organization Owners"]
    OWNER --> TEAM["Teams"]
    TEAM --> PROJECT["Projects"]
    PROJECT --> TASK["Tasks & Subtasks"]
    ORG --> BACK["Implemented Flask Backend"]
    BACK --> AUTH["Authentication · JWT"]
    BACK --> RBAC["Role-Based Access"]
    BACK --> DB["SQLAlchemy · Database"]
```

**Backend foundation**

- Flask application factory.
- SQLAlchemy and database migrations.
- Authentication and authorization.
- Organizations, teams and user management.
- UUID-based user identification.
- Role-based access control.

**Technology stack**

<img src="https://skillicons.dev/icons?i=python,flask,postgres,redis,docker,nginx,bootstrap&theme=dark" width="100%" alt="PMS technologies"/>

<sub>The project is in progress. Some product modules and UI features remain planned or prototyped.</sub>

<a href="https://github.com/Awab7-ux/PMS">
<img src="https://img.shields.io/badge/Explore_PMS-Repository-06B6D4?style=for-the-badge&logo=github" alt="PMS repository"/>
</a>

---

## 03. Other Engineering Projects

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

### Programming Languages

<img src="https://skillicons.dev/icons?i=python,js,ts,html,css&theme=dark" alt="Programming languages"/>

### Backend Engineering

<img src="https://skillicons.dev/icons?i=flask,fastapi&theme=dark" alt="Backend technologies"/>

<sub>SQLAlchemy · REST APIs · JWT · RBAC · Celery · Layered Architecture</sub>

### Frontend & Mobile Development

<img src="https://skillicons.dev/icons?i=react,vite,tailwind,bootstrap&theme=dark" alt="Frontend technologies"/>

<sub>React Native · Expo · TypeScript · Responsive Design · RTL Interfaces</sub>

### Databases & Data Engineering

<img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis&theme=dark" alt="Database technologies"/>

<sub>SQL · pgvector · Database Migrations · Tenant Isolation</sub>

### AI Engineering

<sub>OpenAI API · Whisper · Groq-hosted LLMs · Sentence Transformers · Embeddings · Semantic Search · AI Workflows</sub>

### Cloud & DevOps

<img src="https://skillicons.dev/icons?i=docker,kubernetes,nginx,githubactions,gcp,vercel&theme=dark" alt="Cloud and DevOps technologies"/>

<sub>Docker Compose · CI/CD · GitHub Actions · Kubernetes · Nginx</sub>

### Development Tools

<img src="https://skillicons.dev/icons?i=git,github,vscode,linux&theme=dark" alt="Development tools"/>

<sub>pytest · API Testing · Git Workflows · Automated Testing</sub>

</div>

---

## 05. Engineering Principles

| Principle | My Approach |
|---|---|
| Security First | Keep secrets server-side and enforce authorization at API boundaries. |
| Tenant Isolation | Scope organization data at every query and test isolation boundaries. |
| Maintainable Architecture | Separate routers, services, repositories and schemas. |
| Reliable Delivery | Use automated tests, CI workflows and containerized environments. |
| Practical AI | Integrate AI into real workflows with clear limitations and safeguards. |
| Engineering Transparency | Clearly distinguish implemented features from prototypes and roadmap items. |

---

## 06. Certifications

<div align="center">

<a href="https://www.credly.com/badges/1b787526-1c64-41a5-9687-d5ea45afe68c">
<img src="https://img.shields.io/badge/IBM-Generative_AI_Engineering-0F62FE?style=for-the-badge&logo=ibm&logoColor=white" alt="IBM Generative AI Engineering"/>
</a>

<br/><br/>

<a href="https://www.credly.com/badges/db59f61d-ce17-44b6-aac2-22ac3f78406a">
<img src="https://img.shields.io/badge/IBM-DevOps_%26_Software_Engineering-0F62FE?style=for-the-badge&logo=ibm&logoColor=white" alt="IBM DevOps and Software Engineering"/>
</a>

<br/><br/>

<a href="https://www.credly.com/badges/50ee3989-fa66-4d57-a522-22a7f1e35f52">
<img src="https://img.shields.io/badge/Coursera-Continuous_Integration_%26_Continuous_Delivery-06B6D4?style=for-the-badge&logo=coursera&logoColor=white" alt="CI/CD certification"/>
</a>

<sub>Verify credentials through the linked Credly pages. These are professional certificates and course-completion credentials, not proctored vendor certification exams.</sub>

</div>

---

## 07. GitHub Analytics

<div align="center">

<img width="49%" src="https://github-readme-stats.shion.dev/api?username=Awab7-ux&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0A192F&title_color=38BDF8&icon_color=06B6D4&text_color=CBD5E1" alt="GitHub statistics"/>

<img width="49%" src="https://github-readme-stats.shion.dev/api/top-langs/?username=Awab7-ux&layout=compact&theme=tokyonight&hide_border=true&bg_color=0A192F&title_color=38BDF8&text_color=CBD5E1" alt="Most used programming languages"/>

<br/><br/>

<img width="70%" src="https://streak-stats.demolab.com/?user=Awab7-ux&theme=tokyonight&hide_border=true&background=0A192F&ring=06B6D4&fire=38BDF8&currStreakLabel=38BDF8" alt="GitHub contribution streak"/>

<br/><br/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Awab7-ux&bg_color=0A192F&color=38BDF8&line=2563EB&point=E6F1FF&area=true&hide_border=true" alt="GitHub contribution activity graph"/>

<br/><br/>

<img width="100%" src="https://github-profile-trophy.vercel.app/?username=Awab7-ux&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7" alt="GitHub trophies"/>

<br/><br/>

### Contribution Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Awab7-ux/Awab7-ux/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Awab7-ux/Awab7-ux/output/github-snake.svg"/>
  <img alt="Animated GitHub contribution snake" src="https://raw.githubusercontent.com/Awab7-ux/Awab7-ux/output/github-snake-dark.svg" width="100%"/>
</picture>

</div>

---

## 08. Let's Connect

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=0:0A192F,50:38BDF8,100:06B6D4" width="100%" alt="Decorative separator"/>

**I build software that solves problems, connects systems and creates meaningful impact.**

I'm open to engineering opportunities, technical discussions and collaborations on innovative software projects.

<br/>

<a href="https://www.linkedin.com/in/awab-imad-5a541637b">
<img src="https://img.shields.io/badge/LinkedIn-Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"/>
</a>
<a href="mailto:awabpasta@gmail.com">
<img src="https://img.shields.io/badge/Email-Send_a_Message-06B6D4?style=for-the-badge&logo=gmail" alt="Email"/>
</a>
<a href="https://github.com/Awab7-ux">
<img src="https://img.shields.io/badge/GitHub-Explore_My_Work-181717?style=for-the-badge&logo=github" alt="GitHub"/>
</a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:06B6D4,50:0B3C8C,100:071426" width="100%" alt="Decorative animated footer"/>

<sub>Designed and engineered by Awab Imad · Always building. Always learning.</sub>

</div>
