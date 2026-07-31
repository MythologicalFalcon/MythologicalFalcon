<div align="center">
  <h2>
    Hi, I'm <span style="color:#F5F752;">Anirudh Maheswaram</span><br>
    Senior Software Engineer • Full Stack • AI / LLM
  </h2>
  <h3>Full-stack engineer building production AI agents and operational tooling for infrastructure teams</h3>
  <span>React • TypeScript • Python • GraphQL • Java • LLM Agents • RAG • Kubernetes • PostgreSQL</span>
</div>

<div align="center">
  <a href="#profile">Profile</a> ·
  <a href="#value">What I bring</a> ·
  <a href="#achievements">Achievements</a> ·
  <a href="#experience">Experience</a> ·
  <a href="#projects">Projects</a> ·
  <a href="#stack">Stack</a> ·
  <a href="#fit">Focus</a>
</div>

<a id="profile"></a>

## Short profile

I build software for the people who keep systems running. Six years across network
management at Ericsson and incident response at Meta: dashboards, real-time event
streams, alerting, and now autonomous agents in the live incident path. I own a
feature from the React surface through the API layer to the service behind it.

Six years of paid engineering. Java, Spring, and Angular platform work at TCS, then
full-stack React, GraphQL, and Python at Meta via HCLTech. The domain has not changed
much in that time. It is operational tooling for infrastructure teams: incident
management, oncall workflows, network monitoring, and now the AI layer on top of them.

The AI work runs in production. I wrote the agent loop, the tool-calling, the
guardrails, RAG over operational history, and an eval harness that measures output
quality.

Email: [anirudhmaheswaram@gmail.com](mailto:anirudhmaheswaram@gmail.com)
LinkedIn: [anirudh-maheswaram](https://www.linkedin.com/in/anirudh-maheswaram/)
GitHub: [github.com/MythologicalFalcon](https://github.com/MythologicalFalcon)
Location: Texas, United States

<a id="value"></a>

## What I bring

I'm most useful where a team needs an engineer who can:

- ship full-stack features end to end: React and TypeScript on the front, GraphQL and Python or Java services behind
- design LLM systems that survive contact with production: agent loops, tool-calling, guardrails, retrieval, and evals that catch regressions before release
- work in the operations domain natively: incidents, oncall rotations, alerting, runbooks, telemetry, fault management
- build backend services on Spring Boot, FastAPI, Kafka, PostgreSQL, Docker, and Kubernetes
- take a task from stakeholder request through design, implementation, rollout, and support
- lead a team: assign work, review output, mentor, keep delivery on track

<a id="achievements"></a>

## Key achievements

### AI and LLM engineering

- Built an agentic remediation system on Claude and OpenAI Codex. I wrote the agent loop, the tool-calling, and the guardrails. It runs runbook steps on its own during live incidents, so the oncall engineer does not have to.
- Built LLM auto-triage. It classifies incident severity and routes to the correct oncall rotation, so nobody has to sit between the alert firing and someone acknowledging it.
- Implemented RAG over runbooks and past incidents, so remediation grounds in what the team actually did before.
- Built an eval harness. It measures output quality and catches regressions before release.
- Added automated summarization of incident threads and oncall handoffs. Context survives a rotation change.

### Full-stack platform engineering

- Full-stack work on internal incident-response tooling used by thousands of engineers company-wide. React, GraphQL, Python, Hack.
- Built and maintained an operator dashboard in Angular 6 against Java Spring Boot services. Network teams use it to see across Ericsson router fleets.
- Migrated a multi-page UI to a single-page application in Angular, TypeScript, and ES6. Load times and navigation both improved.
- Built a secure remote-access dashboard in Python and React with role-based access control. Time to reach critical data dropped 30%, at 99.9% uptime.

### Backend, data, and infrastructure

- Implemented Kafka for real-time event processing. Device events and telemetry move through the platform on it.
- Built Spring microservices on JBoss EAP7, deployed with Docker and Kubernetes. JMS handles inter-service messaging.
- Cut memory consumption by 2 GB through profiling.
- Automated build and deployment with Jenkins and GitHub Actions.

### Mobile and side projects

- Shipped an offline-first Android app in React Native and TypeScript. The card catalog, wallet, and recommendation engine all run with no network.
- Replaced Google Maps with MapLibre and OpenFreeMap. No API keys to manage, no third-party cost in the release.
- Built a release pipeline on GCP Cloud Build. It produces signed Android App Bundles to the Play Store internal track.
- Wallet data is stored on device with hardware-backed encryption.

<a id="experience"></a>

## Experience

### HCLTech (Client: Meta)

**Senior Software Engineer**
**November 2024 - Present · Remote**

- Full-stack development on internal incident-response tooling used by thousands of engineers company-wide.
- Built an agentic remediation system on Claude and Codex: agent loop, tool-calling, guardrails, autonomous runbook execution during live incidents.
- Built LLM auto-triage that classifies incident severity and routes to the correct oncall rotation.
- Implemented RAG over runbooks and past incidents. Built an eval harness that measures output quality and catches regressions before release.
- Own feature requests, workflow design, and production bug fixes across both platforms.
- Stack: React, GraphQL, Python, Hack, Claude API, OpenAI Codex.

### Local Grown Salads (via Arizona State University)

**Software Engineer & Team Lead (Volunteer)**
**July 2024 - November 2024 · Tempe, AZ**

- Led a team of 6 engineers while contributing hands-on: assigned work, reviewed output, mentored juniors.
- Built a secure dashboard for remote data access. Time to reach critical data dropped 30%, at 99.9% uptime.
- Implemented role-based access control and maintained PostgreSQL databases.
- Built CI/CD pipelines with GitHub Actions for automated build and deployment.
- Stack: Python, React, HTML/CSS, PostgreSQL, GitHub Actions, Jira, Confluence.

### Arizona State University

**Student Worker**
**October 2022 - May 2024 · Tempe, AZ**

- Diagnosed and resolved issues across ASU's application and student portals in Java and Angular.
- Built a Python script that generates statistical reports on admissions data for internal decision-making.
- Stack: Java, Angular, Python, SQL.

### Tata Consultancy Services (Client: Ericsson)

**Developer**
**June 2018 - October 2022, 4+ years · Hyderabad, India**

- Full-stack development of a network management platform for Ericsson routers, from the operator dashboard through to the backend services handling device data.
- Kafka for real-time event processing across the router fleet. JMS for inter-service messaging.
- Spring microservices on JBoss EAP7, deployed with Docker and Kubernetes.
- Cut memory consumption by 2 GB through profiling. Migrated the UI to an SPA, which improved load times.
- Stack: Angular 6, TypeScript, ES6, Java, Spring Boot, REST, JMS, Kafka, Docker, Kubernetes, JBoss EAP7, Jenkins.

### Earlier roles

**2017 - 2018**

- TCS intern. Emulated software-defined networks with Mininet and OpenDaylight, and implemented shortest-path and alternate-path routing.
- ONGC intern. SCADA line and satellite communications for industrial telemetry. Analysed radio communications and stored sensor data at lower memory utilisation.

<a id="projects"></a>

## Selected projects

| Project | What it proves | Technologies |
| --- | --- | --- |
| [WhichCard](https://github.com/MythologicalFalcon/whichcard) | Offline-first mobile architecture, on-device encryption, full CI/CD to a signed release artifact | React Native, Expo, TypeScript, MapLibre, Supabase, GCP Cloud Build, Docker |
| [Trade](https://github.com/MythologicalFalcon/trade) | Production-shaped full-stack system: auth with row-level security, orchestration, ML scoring, API layer, web and mobile clients | FastAPI, GraphQL, React, Vite, Supabase, Firestore, Airflow, scikit-learn, Capacitor |

### WhichCard

Recommends the best credit card to use at any merchant to maximise cashback, points,
or miles. The card catalog, wallet, and recommendation engine all run with no network.
I dropped Google Maps for MapLibre and OpenFreeMap to get rid of API key management
entirely. It ships to the Play Store internal track through GCP Cloud Build.

### Trade

A five-stage stock analysis pipeline that produces buy and sell recommendations:
technical indicators, company fundamentals, 13-pattern chart detection, news sentiment
via VADER, and a weighted decision scorer that fine-tunes on ML once there are enough
samples. Supabase Postgres with row-level security backs per-user watchlists. Airflow
runs nightly batch analysis, and Firestore drives realtime pipeline status in the UI.

<a id="stack"></a>

## Technology stack

**Languages:** TypeScript, JavaScript/ES6, Python, Java, SQL, Hack/PHP, HTML5, CSS3
**AI / LLM:** Claude (Anthropic API), OpenAI Codex, agent loop design, tool-calling, RAG, LLM evals, prompt engineering, auto-triage and classification, summarization
**Frontend:** React, React Native, Expo, Angular 6+, Vite, Capacitor, SPA architecture
**Backend:** GraphQL, FastAPI, Spring Boot, REST APIs, Kafka, JMS, microservices, event-driven architecture
**Databases:** PostgreSQL, Supabase (Postgres, Auth, RLS), Firebase Firestore, SQL Server
**Infrastructure:** Docker, Kubernetes, JBoss EAP7, Jenkins, GitHub Actions, GCP Cloud Build, Airflow, Git
**Data / ML:** scikit-learn, Airflow, yfinance, VADER sentiment, statistical reporting
**Domain:** incident management, oncall tooling, network management, SDN (Mininet/OpenDaylight), telemetry, SCADA
**Practices:** CI/CD, RBAC, memory profiling, performance optimisation, technical documentation, Agile/Scrum, team leadership

<a id="fit"></a>

## Focus

The work I do best, and want more of.

Senior full-stack engineering. React, GraphQL, Python and Java services, product work
and internal platforms.

AI and LLM engineering. Agent systems, retrieval, tool-calling, guardrails, and the
evals that make any of it trustworthy.

Platform and developer productivity. Internal tools and workflow design.

SRE tooling and incident response. Six years of operational tooling for infrastructure
teams, from router fleet monitoring to oncall automation.

<div align="center">
  <sub>2026</sub>
</div>
