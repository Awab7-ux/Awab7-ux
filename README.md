<div align="center">

<img src="assets/banner.svg" alt="Awab Imad - Software Engineer, Backend and Full-Stack Developer, AI-Integrated Systems" width="100%"/>

<a href="https://github.com/Awab7-ux">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3200&pause=1000&color=38BDF8&center=true&vCenter=true&width=760&lines=Building+intelligent+software+systems;Scalable+backend+architectures+%7C+Flask+%26+FastAPI;AI-integrated+applications+%7C+React+%26+TypeScript;Currently+deepening+Cloud+%26+DevOps+engineering" alt="Typing animation: building intelligent software systems, scalable backend architectures, AI-integrated applications, deepening cloud and DevOps engineering"/>
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0A192F)](https://www.linkedin.com/in/awab-imad-5a541637b)
[![Email](https://img.shields.io/badge/Email-Get_in_touch-06B6D4?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0A192F)](mailto:awabpasta@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Awab7--ux-2563EB?style=for-the-badge&logo=github&logoColor=white&labelColor=0A192F)](https://github.com/Awab7-ux)

<sub>**Current focus:** AI-integrated products &nbsp;·&nbsp; multi-tenant backends &nbsp;·&nbsp; Cloud &amp; DevOps</sub>

</div>

<br/>

<div align="center">

[About](#about) · [Sahatak](#featured-sahatak) · [Lexera](#lexera) · [CloudOps](#cloudops-platform) · [PMS](#project-management-system-pms) · [Other work](#other-engineering-projects) · [Skills](#technical-skills) · [Certifications](#certifications) · [Analytics](#github-analytics) · [Contact](#contact)

</div>

<br/>

## About

I design, build and integrate complete software systems: secure REST backends, clean React and React Native clients, and AI features that sit inside real product workflows. I enjoy turning complex ideas into practical, usable software.

| Engineering focus | What it looks like in my projects |
| :-- | :-- |
| **Backend and APIs** | Flask and FastAPI services, layered architecture, JWT authentication, role-based access |
| **Full-stack delivery** | React and TypeScript web apps, a React Native / Expo mobile app, Arabic and English interfaces |
| **AI integration** | LLM triage and risk analysis, speech-to-text, semantic search with pgvector |
| **Systems and data** | PostgreSQL, MySQL, SQLite, Redis, Celery background processing, multi-tenant data isolation |
| **Cloud and DevOps** | Docker, Docker Compose, GitHub Actions, Kubernetes manifests (local kind), Nginx |

Computing graduate (B.Sc.), open to **Software Engineer, Backend, Full-Stack and AI Engineer** roles, and to collaboration on open-source and innovative technology projects.

<br/>

## Featured: Sahatak

<div align="center">

### Sahatak (صحتك) · Integrated Telemedicine Platform

*Bilingual (Arabic / English) digital healthcare: patients, doctors and administrators on one shared backend.*

</div>

Access to healthcare can be limited by distance, transportation, scarce medical resources and unreliable connectivity. Sahatak aims to reduce those barriers with remote consultations, appointment booking, medical records and AI-assisted preliminary symptom assessment. The engineering challenge was making several clients, a REST backend and external services behave as one coherent system.

<img src="assets/sahatak-architecture.svg" alt="Sahatak architecture: patient mobile app and web portal connect to a Flask REST API, which uses a database, OpenAI and Jitsi Meet" width="100%"/>

### The three components

| Component | Stack | Repository |
| :-- | :-- | :-- |
| **Patient mobile app** | React Native · Expo · TypeScript | [`Sahatak-Telemedicine-App2/sahatak-mobile`](https://github.com/Awab7-ux/Sahatak-Telemedicine-App2/tree/main/sahatak-mobile) |
| **Web portal** for doctors, patients and admins | HTML · JavaScript · Bootstrap 5 (RTL support) | [`sahataksudan-collab/Sahatak`](https://github.com/sahataksudan-collab/Sahatak) (team repository) |
| **Shared REST backend** | Python · Flask · SQLAlchemy · JWT | [`sahataksudan-collab/Sahatak`](https://github.com/sahataksudan-collab/Sahatak) (team repository) |

<sub>The Awab7-ux repository also contains a companion Flask + PostgreSQL backend with Docker Compose (auth, doctors, appointments, records, pharmacy, clinics, notifications, chat) and a web prototype. The deployed web stack uses MySQL; local development falls back to SQLite.</sub>

### Patient mobile app modules

<table>
  <tr>
    <td width="33%" valign="top"><b>Authentication and profile</b><br/><sub>Registration, login, profile and user settings</sub></td>
    <td width="33%" valign="top"><b>Doctor discovery</b><br/><sub>Browse doctors and view profiles</sub></td>
    <td width="33%" valign="top"><b>Appointments</b><br/><sub>Booking flow, details and history</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>Medical records</b><br/><sub>Records and care-summary screens</sub></td>
    <td valign="top"><b>Video consultation</b><br/><sub>Jitsi Meet sessions configured by the backend</sub></td>
    <td valign="top"><b>Messaging</b><br/><sub>Patient-doctor chat over HTTP polling</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>Pharmacy</b><br/><sub>Products and cart workflows</sub></td>
    <td valign="top"><b>Clinic locator</b><br/><sub>Map-based clinic exploration</sub></td>
    <td valign="top"><b>Checkups and notifications</b><br/><sub>Medical checkup screen, notification center, Calm Mode setting</sub></td>
  </tr>
</table>

### Doctor and admin web portal

Doctor authentication and verification, dashboards, availability management, electronic health records, prescriptions, patient messaging, video consultations, notifications, calendar sync, and admin and support tooling, all served by the shared backend.

### AI-assisted symptom assessment

<img src="assets/sahatak-ai-workflow.svg" alt="Sahatak AI workflow: text or voice symptoms go through Whisper and a GPT triage prompt, producing telemedicine, in-person or emergency outcomes" width="100%"/>

Voice input is transcribed with OpenAI Whisper; a GPT triage prompt (language-matched to the patient) recommends a care path. The result is a **preliminary assessment and does not replace professional medical diagnosis.**

### Patient journey

<img src="assets/sahatak-journey.svg" alt="Conceptual Sahatak patient journey from opening the app to follow-up care" width="100%"/>

### Engineering highlights

| | |
| :-- | :-- |
| **56** registered users | **50+** AI symptom-assessment queries processed |
| **3** coordinated components | **AR / EN** bilingual experience |

<sub>User and query figures are historical project metrics, not live counters. The mobile APK has not been publicly released.</sub>

Technical notes: JWT authentication · Jitsi Meet integration · OpenAI GPT and Whisper · messaging deliberately built on **HTTP polling rather than WebSockets** for proxy compatibility.

<br/>

## Lexera

<div align="center">

### AI Contract Intelligence SaaS Platform

</div>

A multi-tenant platform that automates legal-contract review: risk analysis, semantic search and renewal alerts for organizations with large contract portfolios.

<img src="assets/lexera-architecture.svg" alt="Lexera architecture: React frontend, Flask API with tenant isolation, Celery and Redis workers, AI services, PostgreSQL with pgvector" width="100%"/>

<table>
  <tr>
    <td width="50%" valign="top"><b>Multi-tenant security</b><br/><sub>Organization-scoped data on every query, JWT auth, admin / manager / viewer roles, automated tenant-isolation tests</sub></td>
    <td width="50%" valign="top"><b>AI contract analysis</b><br/><sub>LLM risk analysis flags problematic clauses and missing terms; version-comparison summaries; voice notes with speech-to-text</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>Semantic search</b><br/><sub>PostgreSQL pgvector with local sentence-transformer embeddings to reduce API cost</sub></td>
    <td valign="top"><b>Background processing</b><br/><sub>Celery and Redis for analysis, transcription and scheduled renewal alerts</sub></td>
  </tr>
</table>

<img src="https://skillicons.dev/icons?i=python,flask,react,ts,vite,tailwind,postgres,redis,docker,vercel&theme=dark" alt="Lexera stack: Python, Flask, React, TypeScript, Vite, Tailwind CSS, PostgreSQL, Redis, Docker, Vercel"/>

Deployed across Railway, Neon, Upstash and Vercel. &nbsp;[![Lexera repository](https://img.shields.io/badge/Repository-Lexera-818CF8?style=flat-square&logo=github&logoColor=white&labelColor=0A192F)](https://github.com/Awab7-ux/Lexera)

<br/>

## CloudOps Platform

<div align="center">

### Cloud Infrastructure and Deployment Management (in active development)

</div>

A FastAPI backend with a React dashboard for managing applications, deployments, logs and alerts, built to practice production-style DevOps: testing, containers, CI and Kubernetes.

<img src="assets/cloudops-pipeline.svg" alt="CloudOps delivery pipeline: GitHub Actions CI, Docker Compose, local Kubernetes, with monitoring and Terraform as roadmap items" width="100%"/>

<table>
  <tr>
    <td width="33%" valign="top"><b>API infrastructure</b><br/><sub>Layered routers, services, repositories and schemas; request-ID logging; pagination; around 240 pytest test functions</sub></td>
    <td width="33%" valign="top"><b>Containerization</b><br/><sub>Docker images (non-root backend), Compose, React served through Nginx</sub></td>
    <td width="33%" valign="top"><b>CI and Kubernetes</b><br/><sub>GitHub Actions for backend and frontend; Deployment, Service, ConfigMap and PVC manifests for local kind</sub></td>
  </tr>
</table>

<img src="https://skillicons.dev/icons?i=python,fastapi,react,ts,vite,docker,nginx,kubernetes,githubactions,sqlite&theme=dark" alt="CloudOps stack: Python, FastAPI, React, TypeScript, Vite, Docker, Nginx, Kubernetes, GitHub Actions, SQLite"/>

**Roadmap (not yet implemented):** Terraform and Prometheus / Grafana monitoring. **Known limits:** SQLite, no authentication yet, some dashboard pages use labeled demo data. &nbsp;[![CloudOps repository](https://img.shields.io/badge/Repository-cloudops--platform-2563EB?style=flat-square&logo=github&logoColor=white&labelColor=0A192F)](https://github.com/Awab7-ux/cloudops-platform)

<br/>

## Project Management System (PMS)

<div align="center">

### Multi-Tenant Project Management SaaS (active development)

</div>

A project-management platform for organizations and teams, inspired by tools such as Jira, Asana and Trello. The backend foundation (authentication, organizations, teams, users, role-based access) is implemented with a Flask application factory, SQLAlchemy and migrations; the system design, ERD and use-case diagrams are documented in the repository.

<img src="assets/pms-hierarchy.svg" alt="PMS hierarchy from super admin to organizations, teams, projects and tasks, with implemented and planned parts distinguished" width="100%"/>

<table>
  <tr>
    <td width="33%"><img src="https://raw.githubusercontent.com/Awab7-ux/PMS/main/images/dashboard.png" alt="PMS workspace dashboard screenshot" width="100%"/></td>
    <td width="33%"><img src="https://raw.githubusercontent.com/Awab7-ux/PMS/main/images/calendar.png" alt="PMS calendar screenshot" width="100%"/></td>
    <td width="33%"><img src="https://raw.githubusercontent.com/Awab7-ux/PMS/main/images/reports.png" alt="PMS reports screenshot" width="100%"/></td>
  </tr>
</table>

<img src="https://skillicons.dev/icons?i=python,flask,postgres,redis,docker,nginx,bootstrap&theme=dark" alt="PMS planned stack: Python, Flask, PostgreSQL, Redis, Docker, Nginx, Bootstrap"/>

<sub>Planned stack per the design docs; the project is in progress and not complete.</sub> &nbsp;[![PMS repository](https://img.shields.io/badge/Repository-PMS-06B6D4?style=flat-square&logo=github&logoColor=white&labelColor=0A192F)](https://github.com/Awab7-ux/PMS)

<br/>

## Other Engineering Projects

| Project | Purpose | Stack | Status |
| :-- | :-- | :-- | :-- |
| [accounts](https://github.com/Awab7-ux/accounts) | Accounts REST service with CI workflow and security headers | Python · Docker · GitHub Actions | Coursework |
| [tax-calculator-devops-capstone](https://github.com/Awab7-ux/tax-calculator-devops-capstone) | Tax calculation service with tests and Kubernetes manifests | Python · Flask · Docker · Kubernetes · pytest | Coursework |
| [ci-cd-final-project](https://github.com/Awab7-ux/ci-cd-final-project) | Small service with automated tests and container build | Node.js · Docker | Coursework |
| [xrwvm-fullstack_developer_capstone](https://github.com/Awab7-ux/xrwvm-fullstack_developer_capstone) | Full-stack capstone with CI and deployment configuration | Django · Docker | Coursework |
| [onlinecourse-final-project](https://github.com/Awab7-ux/onlinecourse-final-project) | Online course app with an assessment feature | Django | Coursework |
| [Back-end-Development-Capstone](https://github.com/Awab7-ux/Back-end-Development-Capstone) | Concert-site backend capstone | Django | Coursework |
| [med_appt](https://github.com/Awab7-ux/med_appt) | Online doctor-appointment booking front end | JavaScript · HTML · CSS | Coursework |

<br/>

## Technical Skills

<table>
  <tr><td width="28%"><b>Languages</b></td><td><img src="https://skillicons.dev/icons?i=python,js,ts,html,css&theme=dark" alt="Python, JavaScript, TypeScript, HTML, CSS"/></td></tr>
  <tr><td><b>Backend</b></td><td><img src="https://skillicons.dev/icons?i=flask,fastapi&theme=dark" alt="Flask, FastAPI"/> &nbsp;<sub>SQLAlchemy · REST APIs · JWT · Celery</sub></td></tr>
  <tr><td><b>Frontend and mobile</b></td><td><img src="https://skillicons.dev/icons?i=react,vite,tailwind,bootstrap&theme=dark" alt="React, Vite, Tailwind CSS, Bootstrap"/> &nbsp;<sub>React Native · Expo</sub></td></tr>
  <tr><td><b>Databases</b></td><td><img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis&theme=dark" alt="PostgreSQL, MySQL, SQLite, Redis"/> &nbsp;<sub>pgvector</sub></td></tr>
  <tr><td><b>AI engineering</b></td><td><sub>OpenAI API · Whisper · Groq-hosted LLMs · sentence-transformers · embeddings · semantic search</sub></td></tr>
  <tr><td><b>Cloud and DevOps</b></td><td><img src="https://skillicons.dev/icons?i=docker,kubernetes,nginx,githubactions,gcp,vercel&theme=dark" alt="Docker, Kubernetes, Nginx, GitHub Actions, Google Cloud, Vercel"/></td></tr>
  <tr><td><b>Testing and tools</b></td><td><img src="https://skillicons.dev/icons?i=git,github,jest&theme=dark" alt="Git, GitHub, Jest"/> &nbsp;<sub>pytest · API and tenant-isolation testing</sub></td></tr>
  <tr><td><b>Learning next</b></td><td><sub>Terraform · Prometheus / Grafana · scalable system design</sub></td></tr>
</table>

### Engineering principles

- **Isolate tenants by design:** scope every query by organization and test the boundary.
- **Layer the backend:** routers, services, repositories and schemas keep logic testable.
- **Keep secrets server-side:** environment-based configuration, containers running as non-root.
- **Be honest about status:** shipped, in progress and roadmap are labeled separately.

<br/>

## Certifications

<div align="center">

[![IBM Generative AI Engineering Professional Certificate](https://img.shields.io/badge/Professional_Certificate-IBM_Generative_AI_Engineering-0F62FE?style=for-the-badge&logo=ibm&logoColor=white&labelColor=0A192F)](https://www.credly.com/badges/1b787526-1c64-41a5-9687-d5ea45afe68c)

[![IBM DevOps and Software Engineering Professional Certificate](https://img.shields.io/badge/Professional_Certificate-IBM_DevOps_%26_Software_Engineering-0F62FE?style=for-the-badge&logo=ibm&logoColor=white&labelColor=0A192F)](https://www.credly.com/badges/db59f61d-ce17-44b6-aac2-22ac3f78406a)

[![Continuous Integration and Continuous Delivery CI/CD](https://img.shields.io/badge/Course_Badge-CI%2FCD_(Coursera)-06B6D4?style=for-the-badge&logo=coursera&logoColor=white&labelColor=0A192F)](https://www.credly.com/badges/50ee3989-fa66-4d57-a522-22a7f1e35f52)

<sub>Professional certificates and course-completion badges delivered via Coursera and verifiable on Credly. None is a proctored vendor exam.</sub>

</div>

<br/>

## GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.shion.dev/api?username=Awab7-ux&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0A192F&title_color=38BDF8&icon_color=06B6D4&text_color=CBD5E1" alt="Awab7-ux GitHub statistics"/>
<img height="170" src="https://github-readme-stats.shion.dev/api/top-langs/?username=Awab7-ux&layout=compact&theme=tokyonight&hide_border=true&bg_color=0A192F&title_color=38BDF8&text_color=CBD5E1" alt="Awab7-ux most-used languages"/>

<img src="https://streak-stats.demolab.com/?user=Awab7-ux&theme=tokyonight&hide_border=true&background=0A192F&ring=06B6D4&fire=38BDF8&currStreakLabel=38BDF8" alt="Awab7-ux contribution streak"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Awab7-ux&bg_color=0A192F&color=38BDF8&line=2563EB&point=E6F1FF&area=true&hide_border=true" alt="Awab7-ux contribution activity graph" width="100%"/>

<img src="https://github-profile-trophy.vercel.app/?username=Awab7-ux&theme=onedark&no-frame=true&no-bg=true&margin-w=6&column=7" alt="Awab7-ux GitHub trophies"/>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Awab7-ux/Awab7-ux/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Awab7-ux/Awab7-ux/output/github-snake.svg"/>
  <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/Awab7-ux/Awab7-ux/output/github-snake-dark.svg"/>
</picture>

</div>

<br/>

## Contact

<div align="center">

*I build software that is reliable, well-tested and honest about what it does. Let's talk about engineering roles or collaboration.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Awab_Imad-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0A192F)](https://www.linkedin.com/in/awab-imad-5a541637b)
[![Email](https://img.shields.io/badge/Email-awabpasta%40gmail.com-06B6D4?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0A192F)](mailto:awabpasta@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Awab7--ux-2563EB?style=for-the-badge&logo=github&logoColor=white&labelColor=0A192F)](https://github.com/Awab7-ux)

</div>
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches: [main]

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


          <div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=240&color=0:0A192F,60:0B3C8C,100:06B6D4&text=Awab%20Imad&fontColor=E6F1FF&fontSize=60&fontAlignY=38&desc=Software%20Engineer%20%7C%20Backend%20%26%20Full-Stack%20Developer%20%7C%20AI-Integrated%20Systems&descSize=18&descAlignY=60&animation=fadeIn" alt="Awab Imad - Software Engineer, Backend and Full-Stack Developer, AI-Integrated Systems" width="100%"/>

<a href="https://github.com/Awab7-ux">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3200&pause=1000&color=38BDF8&center=true&vCenter=true&width=760&lines=Building+intelligent+software+systems;Scalable+backend+architectures+%7C+Flask+%26+FastAPI;AI-integrated+applications+%7C+React+%26+TypeScript;Currently+deepening+Cloud+%26+DevOps+engineering" alt="Typing animation: building intelligent software systems, scalable backend architectures, AI-integrated applications, deepening cloud and DevOps engineering"/>
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0A192F)](https://www.linkedin.com/in/awab-imad-5a541637b)
[![Email](https://img.shields.io/badge/Email-Get_in_touch-06B6D4?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0A192F)](mailto:awabpasta@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Awab7--ux-2563EB?style=for-the-badge&logo=github&logoColor=white&labelColor=0A192F)](https://github.com/Awab7-ux)

<sub>**Current focus:** AI-integrated products &nbsp;·&nbsp; multi-tenant backends &nbsp;·&nbsp; Cloud &amp; DevOps</sub>

</div>

<br/>

<div align="center">

[About](#about) · [Sahatak](#featured-sahatak) · [Lexera](#lexera) · [CloudOps](#cloudops-platform) · [PMS](#project-management-system-pms) · [Other work](#other-engineering-projects) · [Skills](#technical-skills) · [Certifications](#certifications) · [Analytics](#github-analytics) · [Contact](#contact)

</div>

<br/>

## About

I design, build and integrate complete software systems: secure REST backends, clean React and React Native clients, and AI features that sit inside real product workflows. I enjoy turning complex ideas into practical, usable software.

| Engineering focus | What it looks like in my projects |
| :-- | :-- |
| **Backend and APIs** | Flask and FastAPI services, layered architecture, JWT authentication, role-based access |
| **Full-stack delivery** | React and TypeScript web apps, a React Native / Expo mobile app, Arabic and English interfaces |
| **AI integration** | LLM triage and risk analysis, speech-to-text, semantic search with pgvector |
| **Systems and data** | PostgreSQL, MySQL, SQLite, Redis, Celery background processing, multi-tenant data isolation |
| **Cloud and DevOps** | Docker, Docker Compose, GitHub Actions, Kubernetes manifests (local kind), Nginx |

Computing graduate (B.Sc.), open to **Software Engineer, Backend, Full-Stack and AI Engineer** roles, and to collaboration on open-source and innovative technology projects.

<br/>

## Featured: Sahatak

<div align="center">

### Sahatak (صحتك) · Integrated Telemedicine Platform

*Bilingual (Arabic / English) digital healthcare: patients, doctors and administrators on one shared backend.*

</div>

Access to healthcare can be limited by distance, transportation, scarce medical resources and unreliable connectivity. Sahatak aims to reduce those barriers with remote consultations, appointment booking, medical records and AI-assisted preliminary symptom assessment. The engineering challenge was making several clients, a REST backend and external services behave as one coherent system.

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#0F2A4A','primaryBorderColor':'#38BDF8','lineColor':'#38BDF8','primaryTextColor':'#E6F1FF','fontSize':'14px'}}}%%
flowchart LR
  M["Patient Mobile App<br/>React Native · Expo · TypeScript"] --> API
  W["Web Portal: Doctor · Patient · Admin<br/>HTML · JavaScript · Bootstrap 5"] --> API
  API["Flask REST API<br/>SQLAlchemy · JWT · roles"] --> DB[("Database<br/>MySQL deployed · SQLite local")]
  API --> AI["OpenAI API<br/>GPT triage · Whisper"]
  API --> J["Jitsi Meet<br/>Video consultations"]
```

### The three components

| Component | Stack | Repository |
| :-- | :-- | :-- |
| **Patient mobile app** | React Native · Expo · TypeScript | [`Sahatak-Telemedicine-App2/sahatak-mobile`](https://github.com/Awab7-ux/Sahatak-Telemedicine-App2/tree/main/sahatak-mobile) |
| **Web portal** for doctors, patients and admins | HTML · JavaScript · Bootstrap 5 (RTL support) | [`sahataksudan-collab/Sahatak`](https://github.com/sahataksudan-collab/Sahatak) (team repository) |
| **Shared REST backend** | Python · Flask · SQLAlchemy · JWT | [`sahataksudan-collab/Sahatak`](https://github.com/sahataksudan-collab/Sahatak) (team repository) |

<sub>The Awab7-ux repository also contains a companion Flask + PostgreSQL backend with Docker Compose (auth, doctors, appointments, records, pharmacy, clinics, notifications, chat) and a web prototype. The deployed web stack uses MySQL; local development falls back to SQLite.</sub>

### Patient mobile app modules

<table>
  <tr>
    <td width="33%" valign="top"><b>Authentication and profile</b><br/><sub>Registration, login, profile and user settings</sub></td>
    <td width="33%" valign="top"><b>Doctor discovery</b><br/><sub>Browse doctors and view profiles</sub></td>
    <td width="33%" valign="top"><b>Appointments</b><br/><sub>Booking flow, details and history</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>Medical records</b><br/><sub>Records and care-summary screens</sub></td>
    <td valign="top"><b>Video consultation</b><br/><sub>Jitsi Meet sessions configured by the backend</sub></td>
    <td valign="top"><b>Messaging</b><br/><sub>Patient-doctor chat over HTTP polling</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>Pharmacy</b><br/><sub>Products and cart workflows</sub></td>
    <td valign="top"><b>Clinic locator</b><br/><sub>Map-based clinic exploration</sub></td>
    <td valign="top"><b>Checkups and notifications</b><br/><sub>Medical checkup screen, notification center, Calm Mode setting</sub></td>
  </tr>
</table>

### Doctor and admin web portal

Doctor authentication and verification, dashboards, availability management, electronic health records, prescriptions, patient messaging, video consultations, notifications, calendar sync, and admin and support tooling, all served by the shared backend.

### AI-assisted symptom assessment

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#0F2A4A','primaryBorderColor':'#38BDF8','lineColor':'#38BDF8','primaryTextColor':'#E6F1FF','fontSize':'14px'}}}%%
flowchart LR
  S["Symptoms<br/>typed text or voice"] -->|voice| WH["Whisper<br/>speech-to-text"]
  S -->|text| G
  WH --> G["GPT triage prompt<br/>replies in patient language"]
  G --> T{"Triage outcome"}
  T --> A["Telemedicine<br/>stored as low risk"]
  T --> B["In-person<br/>stored as medium risk"]
  T --> C["Emergency<br/>stored as critical risk"]
```

Voice input is transcribed with OpenAI Whisper; a GPT triage prompt (language-matched to the patient) recommends a care path. The result is a **preliminary assessment and does not replace professional medical diagnosis.**

### Patient journey

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#0F2A4A','primaryBorderColor':'#38BDF8','lineColor':'#38BDF8','primaryTextColor':'#E6F1FF','fontSize':'14px'}}}%%
flowchart LR
  A["1 Open app<br/>AR / EN"] --> B["2 Authenticate<br/>JWT login"] --> C["3 Find a doctor<br/>search · profiles"] --> D["4 Book appointment<br/>status · history"]
  D --> E["5 AI assessment<br/>preliminary triage"] --> F["6 Consultation<br/>video · messaging"] --> G["7 Records<br/>reports · prescriptions"] --> H["8 Follow-up<br/>notifications"]
```

### Engineering highlights

| | |
| :-- | :-- |
| **56** registered users | **50+** AI symptom-assessment queries processed |
| **3** coordinated components | **AR / EN** bilingual experience |

<sub>User and query figures are historical project metrics, not live counters. The mobile APK has not been publicly released.</sub>

Technical notes: JWT authentication · Jitsi Meet integration · OpenAI GPT and Whisper · messaging deliberately built on **HTTP polling rather than WebSockets** for proxy compatibility.

<br/>

## Lexera

<div align="center">

### AI Contract Intelligence SaaS Platform

</div>

A multi-tenant platform that automates legal-contract review: risk analysis, semantic search and renewal alerts for organizations with large contract portfolios.

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#0F2A4A','primaryBorderColor':'#38BDF8','lineColor':'#38BDF8','primaryTextColor':'#E6F1FF','fontSize':'14px'}}}%%
flowchart TD
  U["User"] --> FE["React Frontend<br/>TypeScript · Vite · Tailwind"] --> API["Flask REST API<br/>JWT · RBAC admin/manager/viewer"]
  API --> TI["Tenant isolation<br/>organization_id on every query"]
  API --> Q["Celery + Redis<br/>async processing · renewal alerts"]
  Q --> AI["AI services<br/>LLM risk analysis · Whisper"]
  Q --> EM["Embeddings<br/>local sentence-transformers"]
  AI --> PG[("PostgreSQL + pgvector<br/>contracts · results · vectors")]
  EM --> PG
  TI --> PG
```

<table>
  <tr>
    <td width="50%" valign="top"><b>Multi-tenant security</b><br/><sub>Organization-scoped data on every query, JWT auth, admin / manager / viewer roles, automated tenant-isolation tests</sub></td>
    <td width="50%" valign="top"><b>AI contract analysis</b><br/><sub>LLM risk analysis flags problematic clauses and missing terms; version-comparison summaries; voice notes with speech-to-text</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>Semantic search</b><br/><sub>PostgreSQL pgvector with local sentence-transformer embeddings to reduce API cost</sub></td>
    <td valign="top"><b>Background processing</b><br/><sub>Celery and Redis for analysis, transcription and scheduled renewal alerts</sub></td>
  </tr>
</table>

<img src="https://skillicons.dev/icons?i=python,flask,react,ts,vite,tailwind,postgres,redis,docker,vercel&theme=dark" alt="Lexera stack: Python, Flask, React, TypeScript, Vite, Tailwind CSS, PostgreSQL, Redis, Docker, Vercel"/>

Deployed across Railway, Neon, Upstash and Vercel. &nbsp;[![Lexera repository](https://img.shields.io/badge/Repository-Lexera-818CF8?style=flat-square&logo=github&logoColor=white&labelColor=0A192F)](https://github.com/Awab7-ux/Lexera)

<br/>

## CloudOps Platform

<div align="center">

### Cloud Infrastructure and Deployment Management (in active development)

</div>

A FastAPI backend with a React dashboard for managing applications, deployments, logs and alerts, built to practice production-style DevOps: testing, containers, CI and Kubernetes.

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#0F2A4A','primaryBorderColor':'#38BDF8','lineColor':'#38BDF8','primaryTextColor':'#E6F1FF','fontSize':'14px'}}}%%
flowchart LR
  DEV["Developer"] --> GH["GitHub"] --> CI["GitHub Actions<br/>backend pytest<br/>frontend lint · build · tests"]
  CI --> DC["Docker Compose<br/>FastAPI + React/Nginx"]
  DC --> K8["Kubernetes manifests<br/>local kind"]
  K8 -.-> MON["Prometheus / Grafana<br/>roadmap"]
  GH -.-> TF["Terraform<br/>roadmap"]
```

<table>
  <tr>
    <td width="33%" valign="top"><b>API infrastructure</b><br/><sub>Layered routers, services, repositories and schemas; request-ID logging; pagination; around 240 pytest test functions</sub></td>
    <td width="33%" valign="top"><b>Containerization</b><br/><sub>Docker images (non-root backend), Compose, React served through Nginx</sub></td>
    <td width="33%" valign="top"><b>CI and Kubernetes</b><br/><sub>GitHub Actions for backend and frontend; Deployment, Service, ConfigMap and PVC manifests for local kind</sub></td>
  </tr>
</table>

<img src="https://skillicons.dev/icons?i=python,fastapi,react,ts,vite,docker,nginx,kubernetes,githubactions,sqlite&theme=dark" alt="CloudOps stack: Python, FastAPI, React, TypeScript, Vite, Docker, Nginx, Kubernetes, GitHub Actions, SQLite"/>

**Roadmap (not yet implemented):** Terraform and Prometheus / Grafana monitoring. **Known limits:** SQLite, no authentication yet, some dashboard pages use labeled demo data. &nbsp;[![CloudOps repository](https://img.shields.io/badge/Repository-cloudops--platform-2563EB?style=flat-square&logo=github&logoColor=white&labelColor=0A192F)](https://github.com/Awab7-ux/cloudops-platform)

<br/>

## Project Management System (PMS)

<div align="center">

### Multi-Tenant Project Management SaaS (active development)

</div>

A project-management platform for organizations and teams, inspired by tools such as Jira, Asana and Trello. The backend foundation (authentication, organizations, teams, users, role-based access) is implemented with a Flask application factory, SQLAlchemy and migrations; the system design, ERD and use-case diagrams are documented in the repository.

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#0F2A4A','primaryBorderColor':'#38BDF8','lineColor':'#38BDF8','primaryTextColor':'#E6F1FF','fontSize':'14px'}}}%%
flowchart LR
  SA["Super Admin"] --> O["Organizations<br/>owners · members · roles"] --> TM["Teams"]
  TM -.-> P["Projects<br/>planned / UI-prototyped"] -.-> TK["Tasks & Subtasks<br/>planned / UI-prototyped"]
  O --> BE["Implemented backend<br/>auth · organizations · teams · users<br/>JWT · RBAC · 18 pytest tests"]
```

<table>
  <tr>
    <td width="33%"><img src="https://raw.githubusercontent.com/Awab7-ux/PMS/main/images/dashboard.png" alt="PMS workspace dashboard screenshot" width="100%"/></td>
    <td width="33%"><img src="https://raw.githubusercontent.com/Awab7-ux/PMS/main/images/calendar.png" alt="PMS calendar screenshot" width="100%"/></td>
    <td width="33%"><img src="https://raw.githubusercontent.com/Awab7-ux/PMS/main/images/reports.png" alt="PMS reports screenshot" width="100%"/></td>
  </tr>
</table>

<img src="https://skillicons.dev/icons?i=python,flask,postgres,redis,docker,nginx,bootstrap&theme=dark" alt="PMS planned stack: Python, Flask, PostgreSQL, Redis, Docker, Nginx, Bootstrap"/>

<sub>Planned stack per the design docs; the project is in progress and not complete.</sub> &nbsp;[![PMS repository](https://img.shields.io/badge/Repository-PMS-06B6D4?style=flat-square&logo=github&logoColor=white&labelColor=0A192F)](https://github.com/Awab7-ux/PMS)

<br/>

## Other Engineering Projects

| Project | Purpose | Stack | Status |
| :-- | :-- | :-- | :-- |
| [accounts](https://github.com/Awab7-ux/accounts) | Accounts REST service with CI workflow and security headers | Python · Docker · GitHub Actions | Coursework |
| [tax-calculator-devops-capstone](https://github.com/Awab7-ux/tax-calculator-devops-capstone) | Tax calculation service with tests and Kubernetes manifests | Python · Flask · Docker · Kubernetes · pytest | Coursework |
| [ci-cd-final-project](https://github.com/Awab7-ux/ci-cd-final-project) | Small service with automated tests and container build | Node.js · Docker | Coursework |
| [xrwvm-fullstack_developer_capstone](https://github.com/Awab7-ux/xrwvm-fullstack_developer_capstone) | Full-stack capstone with CI and deployment configuration | Django · Docker | Coursework |
| [onlinecourse-final-project](https://github.com/Awab7-ux/onlinecourse-final-project) | Online course app with an assessment feature | Django | Coursework |
| [Back-end-Development-Capstone](https://github.com/Awab7-ux/Back-end-Development-Capstone) | Concert-site backend capstone | Django | Coursework |
| [med_appt](https://github.com/Awab7-ux/med_appt) | Online doctor-appointment booking front end | JavaScript · HTML · CSS | Coursework |

<br/>

## Technical Skills

<table>
  <tr><td width="28%"><b>Languages</b></td><td><img src="https://skillicons.dev/icons?i=python,js,ts,html,css&theme=dark" alt="Python, JavaScript, TypeScript, HTML, CSS"/></td></tr>
  <tr><td><b>Backend</b></td><td><img src="https://skillicons.dev/icons?i=flask,fastapi&theme=dark" alt="Flask, FastAPI"/> &nbsp;<sub>SQLAlchemy · REST APIs · JWT · Celery</sub></td></tr>
  <tr><td><b>Frontend and mobile</b></td><td><img src="https://skillicons.dev/icons?i=react,vite,tailwind,bootstrap&theme=dark" alt="React, Vite, Tailwind CSS, Bootstrap"/> &nbsp;<sub>React Native · Expo</sub></td></tr>
  <tr><td><b>Databases</b></td><td><img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis&theme=dark" alt="PostgreSQL, MySQL, SQLite, Redis"/> &nbsp;<sub>pgvector</sub></td></tr>
  <tr><td><b>AI engineering</b></td><td><sub>OpenAI API · Whisper · Groq-hosted LLMs · sentence-transformers · embeddings · semantic search</sub></td></tr>
  <tr><td><b>Cloud and DevOps</b></td><td><img src="https://skillicons.dev/icons?i=docker,kubernetes,nginx,githubactions,gcp,vercel&theme=dark" alt="Docker, Kubernetes, Nginx, GitHub Actions, Google Cloud, Vercel"/></td></tr>
  <tr><td><b>Testing and tools</b></td><td><img src="https://skillicons.dev/icons?i=git,github,jest&theme=dark" alt="Git, GitHub, Jest"/> &nbsp;<sub>pytest · API and tenant-isolation testing</sub></td></tr>
  <tr><td><b>Learning next</b></td><td><sub>Terraform · Prometheus / Grafana · scalable system design</sub></td></tr>
</table>

### Engineering principles

- **Isolate tenants by design:** scope every query by organization and test the boundary.
- **Layer the backend:** routers, services, repositories and schemas keep logic testable.
- **Keep secrets server-side:** environment-based configuration, containers running as non-root.
- **Be honest about status:** shipped, in progress and roadmap are labeled separately.

<br/>

## Certifications

<div align="center">

[![IBM Generative AI Engineering Professional Certificate](https://img.shields.io/badge/Professional_Certificate-IBM_Generative_AI_Engineering-0F62FE?style=for-the-badge&logo=ibm&logoColor=white&labelColor=0A192F)](https://www.credly.com/badges/1b787526-1c64-41a5-9687-d5ea45afe68c)

[![IBM DevOps and Software Engineering Professional Certificate](https://img.shields.io/badge/Professional_Certificate-IBM_DevOps_%26_Software_Engineering-0F62FE?style=for-the-badge&logo=ibm&logoColor=white&labelColor=0A192F)](https://www.credly.com/badges/db59f61d-ce17-44b6-aac2-22ac3f78406a)

[![Continuous Integration and Continuous Delivery CI/CD](https://img.shields.io/badge/Course_Badge-CI%2FCD_(Coursera)-06B6D4?style=for-the-badge&logo=coursera&logoColor=white&labelColor=0A192F)](https://www.credly.com/badges/50ee3989-fa66-4d57-a522-22a7f1e35f52)

<sub>Professional certificates and course-completion badges delivered via Coursera and verifiable on Credly. None is a proctored vendor exam.</sub>

</div>

<br/>

## GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.shion.dev/api?username=Awab7-ux&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0A192F&title_color=38BDF8&icon_color=06B6D4&text_color=CBD5E1" alt="Awab7-ux GitHub statistics"/>
<img height="170" src="https://github-readme-stats.shion.dev/api/top-langs/?username=Awab7-ux&layout=compact&theme=tokyonight&hide_border=true&bg_color=0A192F&title_color=38BDF8&text_color=CBD5E1" alt="Awab7-ux most-used languages"/>

<img src="https://streak-stats.demolab.com/?user=Awab7-ux&theme=tokyonight&hide_border=true&background=0A192F&ring=06B6D4&fire=38BDF8&currStreakLabel=38BDF8" alt="Awab7-ux contribution streak"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Awab7-ux&bg_color=0A192F&color=38BDF8&line=2563EB&point=E6F1FF&area=true&hide_border=true" alt="Awab7-ux contribution activity graph" width="100%"/>

<img src="https://github-profile-trophy.vercel.app/?username=Awab7-ux&theme=onedark&no-frame=true&no-bg=true&margin-w=6&column=7" alt="Awab7-ux GitHub trophies"/>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Awab7-ux/Awab7-ux/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Awab7-ux/Awab7-ux/output/github-snake.svg"/>
  <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/Awab7-ux/Awab7-ux/output/github-snake-dark.svg"/>
</picture>

</div>

<br/>

## Contact

<div align="center">

*I build software that is reliable, well-tested and honest about what it does. Let's talk about engineering roles or collaboration.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Awab_Imad-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0A192F)](https://www.linkedin.com/in/awab-imad-5a541637b)
[![Email](https://img.shields.io/badge/Email-awabpasta%40gmail.com-06B6D4?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0A192F)](mailto:awabpasta@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Awab7--ux-2563EB?style=for-the-badge&logo=github&logoColor=white&labelColor=0A192F)](https://github.com/Awab7-ux)

</div>
